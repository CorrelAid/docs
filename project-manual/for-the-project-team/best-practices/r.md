# R

In this document, you'll find some best practices that we have researched for R projects. Of course, this is an opinionated list. Still, we strongly encourage you to follow those best practices to the best of your ability. It is also very useful to know them in case you end up in a job where those best practices are observed. 

{% hint style="success" %}
We strongly recommend to follow best practices! Those are practices that industry experts have found useful in their work so it can't be wrong to at least try them out.
{% endhint %}

## General best practices

Here are some packages that will make it easier to maintain clean code and ensure working environments. 

* style code with [styler](https://github.com/r-lib/styler)
* implement code linting with [lintr](https://github.com/jimhester/lintr) 
* use [renv](https://github.com/rstudio/renv) to manage packages and keep a consistent environment for all project team participants

## **Reports - RMarkdown**

Reports and other textual outputs should be written using **RMarkdown** to ensure reproducibility and to facilitate proper version control. In certain circumstances, formats like Microsoft Word can be acceptable, e.g. for providing documentation in a familiar format to non-profit partners. 

RMarkdown provides [several output formats](https://rmarkdown.rstudio.com/lesson-9.html). Which one\(s\) you choose depends on the needs of the partner organisation. For example:

* PDF if the organisation needs to provide a report to a third party \(e.g. as part of reporting for a grant\)
* [HTML](https://bookdown.org/yihui/rmarkdown/html-document.html) if it is more for internal use and interactivity like hovering in plots and interactivity in tables is important 
* for longer reports, you might even consider writing a "book" using [bookdown](https://bookdown.org). 

### Resources

If you haven't worked with RMarkdown before:

* [Get started guide](https://rmarkdown.rstudio.com/lesson-1.html)

Embrace the workflow of **RMarkdown driven development**

* [blog post](https://emilyriederer.netlify.app/post/rmarkdown-driven-development/)
* [20 minute talk](https://rstudio.com/resources/rstudioconf-2020/rmarkdown-driven-development/)

-&gt; most CorrelAid reporting projects should aim for the _project stage_.

## Interactive Dashboards 

### flexdashboard - without runtime shiny

{% hint style="success" %}
Recommended solution if data is fixed \(or only updated rarely\) and interactivity needs are not high.
{% endhint %}

Flexdashboard **without runtime Shiny** provide a way to design simple dashboards that are interactive to a certain extent. You can't use Shiny interactivity in those dashboards, but you can make use of [htmlwidgets](https://www.htmlwidgets.org/) that can be linked to a certain extent by using [crosstalk](https://rstudio.github.io/crosstalk/).

Flexdashboards without runtime Shiny have the big advantage over Shiny dashboards and flexdashboards with Shiny that they can be instantly knitted to a static HTML. No server required. Hence, this is the **recommended solution if data is fixed \(or only updated rarely\) and interactivity needs are not high**. If new data is added in the future, the organization must be enabled to re-knit the document themselves in the future. So instead of a "hosting problem", we have a knowledge transfer problem in this case. Still, proper documentation, good handover workshops and technologies that ensure stable environments \(Docker, renv\) can help with solving this problem.

### Shiny

{% hint style="danger" %}
**Do you need Shiny?**

Shiny is great for building interactive dashboards as a data scientist -  it's fun, it's interactive, it's cool! 

However, please keep in mind that in most cases, Shiny dashboards need to be hosted after you have finished developing \(unless if it enough to only run it locally\). As of today, **CorrelAid cannot provide hosting for Shiny apps,** so the organization would need to host it using their own server infrastructure or by paying for [shinyapps.io](https://shinyapps.io). Another issue is maintainability: If you leave the project and a bug appears, who will be there to fix it?

Here are some questions to ask yourself and your teammates to make sure that Shiny is really the right fit:

* Is it a one-time analysis? Maybe a knitted HTML document or flexdasbhoard _without runtime shiny_ \(see above\) would is enough? 
* Will the organization be able to update it with newer data? Are you sure your code will work with new, "unseen" data?
* Again: Will the organization be able to host it?
* Again: Will the organization be able to maintain it?

Please make sure that you have thoroughly thought through these thought-provoking questions the partner organization understands those caveats and has the capabilities to host and maintain it before you start developing a Shiny dashboard. 
{% endhint %}

If you decide that yes, Shiny will best solve the problem at hand, here are some best practices to follow: 

coming soon

### flexdasbhoard - runtime shiny

{% hint style="warning" %}
Still same problems as Shiny w.r.t hosting and maintainability. Good for small dashboards.
{% endhint %}

[Flexdashboard **with runtime Shiny**](https://rmarkdown.rstudio.com/flexdashboard/shiny.html) is a way to design simple dashboards using RMarkdown while still making use of Shiny interactivity \(i.e. inputs and outputs\). This can be useful if you only want to build a small dashboard and you're satisfied with the design that flexdasbhoard has. 

Flexdashboards with runtime Shiny still require a server, so **they do not solve the "hosting problem"**. It is rather a different way to write Shiny apps.

### 









