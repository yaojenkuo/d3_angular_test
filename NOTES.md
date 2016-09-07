## Understanding Directives

Directives give us a way to encapsulate and reuse our visualizations by allowing us to essentially create our own HTML tags. In a way, you’ve already been using directives. The HTML5 `<input>` tags like range and date are essentially the browsers own directives. They’re constructed from a combination of several UI element but expose a simple API. We just don’t get access to their code.

```
<input type="range" min="1" max="1000" value="0" style="width:100%">
```

```
<input type="date" value="2016-04-18">
```