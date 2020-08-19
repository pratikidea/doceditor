# doceditor
Dipendencies
```
JQuery
ng2-pdf-viewer
signature_pad

```

add in angular.json file
```
 "styles": [
          "node_modules/esigndoccontrol/resources/css/doceditor.min.scss",
          "node_modules/esigndoccontrol/resources/css/doceditor.min.css"
]
```


```
 "scripts": [
              "node_modules/esigndoccontrol/resources/js/jquery.min.js",
              "node_modules/esigndoccontrol/resources/js/jquery-ui.min.js",
              "node_modules/esigndoccontrol/resources/js/jquery.contextMenu.min.js",
              "node_modules/esigndoccontrol/resources/js/jquery.ui.position.min.js"
            ]
```
            
            
            
add in index.html in head section
```
<head>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="stylesheet" type="text/css" href="https://code.jquery.com/ui/1.12.1/themes/base/jquery-ui.css">
</head>  

```


Import Module
```
import { iEditorModule } from "esigndoccontrol";


@NgModule({
  
  imports: [
    iEditorModule
  ] 
})

```

Add editor control
```
<i-docsigneditor 
[offlineSaving]="true" 
[reduceHeight]="101"
[zoom]="0.8" [url]="pdfSrc" 
[toolbarBg]="'#e7edee'"
[options]="options"></i-docsigneditor>


pdfSrc="<path/to/pdf/file.pdf>". // in ts file
```

Viewer Control
```
Comming Soon

```
