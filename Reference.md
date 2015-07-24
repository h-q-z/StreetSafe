### Data Source Links

* [Working With Open Data 2014](https://github.com/working-with-open-data-2014/project-organization/wiki/Working-with-Open-Data-2014-Projects)
* [Example: Gentrification Analysis](http://nbviewer.ipython.org/gist/nyborrobyn/f44e87da83efb76831cf)
* [NYC Open Data - Public Safety](https://nycopendata.socrata.com/data?cat=public%20safety)

---

### Technical Links

* [SVG Icons](http://iconmonstr.com/)
* [SVG Tutorial by Jacob Jenkov](http://tutorials.jenkov.com/svg)
* 


---

### Misc Notes

* In order to make a SVG icon scalable, need "viewBox" attribute:

```html 
<svg xmlns="http://www.w3.org/2000/svg"
     xmlns:xlink="http://www.w3.org/1999/xlink"
     viewBox="0 0 128 128">
    <circle cx="64" cy="64" r="64" style="fill: #00ccff;"></circle>
</svg>
```

* Transform via <g>

```html
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
    <g transform="rotate(45 50 50)">
      <line x1="10" y1="10" x2="85" y2="10" style="stroke: #006600;"/>
      <rect x="10" y="20" height="50" width="75" style="stroke: #006600; fill: #006600"/>
      <text x="10" y="90" style="stroke: #660000; fill: #660000">Text grouped with shapes</text>
    </g>
</svg>
```

* 


