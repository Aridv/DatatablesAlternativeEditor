# DatatablesAlternativeEditor
Alternative editor for Datatables, it has two versions: simple and complex

### Before you start
First of all this editor was not made entirely by me, I just found it on google years ago and I couldn't find the website again so unfortunately I can't copy a reference to the original source. If you know where is it, please contact me.

The editor was really simple the first time I used it, as the complexity of the project I worked on increased, I had to add new functionalities and it became the editor which is today. It works in all browsers, I didn't try in the oldest versions but I think you can feel safe.

### What you need
Of course! This is a Datatables editor on client side so you will need JQuery, JQueryUI and Datatables libraries before you can start anything. The exact libraries I'm currently using are the following ones, but keep in mind that you may not need all of them:

* ```JQuery v3.3.1```

* ```JQueryUI v1.11.3```

* ```Bootstrap, as minimum version: v3.3.7```

* ```Datatables, as minimum version: v.1.10.16```

This may get old with time so if you have the latest version of any of these I think it will not suppose a problem.

Other functionalities I'm using, or you may need if you want to exploit the entire functionality of Datatables editor, are these ones:

* ```Datatables Buttons```

* ```Datatables Responsive```

* ```Datatables Select```

* ```Datatables PDFMake```

* ```Datatables JSZip```


### Using the Simple editor
As the name says this editor is simple, and once you check both complex and simple you will notice the differences between both. There will be times when you will need the complex one due to the complexity of the data, but I suggest you, if you can use the simple one, use it and forget the other. You can use both in the same project of course.

The simple editor admits the following properties in your fields:

* ```Title``` -> The name/placeholder attributes from the input field
* ```Name``` -> The id attribute from the input field
* ```Type``` -> The type attribute from the input field, the simple editor admits the next values:
  * ```text``` -> Generates text input field
  * ```date``` -> Generates date input field (in the complex editor you will have the type "datetime")
  * ```readonly``` -> Generates a readonly input field when you modify a record, when adding values the input is hidden
  * ```select``` -> Generates a select input field
* ```Options``` -> The option values from the select field
* ```Msg``` -> For the attribute "data-errorMsg", it is not necessary neither required, but it exists
* ```HoverMsg``` -> For the title attribute
* ```Pattern``` -> For the pattern attribute, it is not necessary neither required in the simple editor, this is simple data!
* ```Special``` -> For the data-special attribute from the input field, it is not necessary neither required
* ```Visible``` -> If the property has a value the field will be hidden (the ideal values are "no", "n" or false)
* ```Required``` -> The field is required, holds a boolean (true or false)
* ```DataType``` -> The only value accepted is "number". Forces the field to be a number before submitting
