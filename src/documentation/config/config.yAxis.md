#### **yAxis** : {<%= type %>}

<% if(defaultValue !== "[object Object]") { %>*default: <%= defaultValue %>* <% }%>

To override any of the default configuration options in a yAxis, include the `yAxis` configuration object in the configuration options that you pass to your Contour constructor.

A yAxis is only useful if your Contour instance uses a [cartesian](#cartesian) frame.

**Example:**

    new Contour({
        el: '.myLineChart',
        yAxis: {
          // yAxis-specific configuration options
        }
      })
    .cartesian()
    .line(data)
    .render()

*[Try it.](<%= jsFiddleLink %>)*

<% if(notes) { %><%= notes %><% } %>

