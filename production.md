### Production

After customize or update real content now you can build for production using `gulp build` command.

```bash
gulp build
```
when you run this `gulp build` production folder automatically build inner on **Aptonic** folder. New build or production folder name is **dist**. In this folder all files and folder as like as **app** folder just `css` and `js` folder is different. Below that structure.


```text
Aptonic
    |-- app
    |    |--
    |    |--
    |    |--
    |-- dist
    |     |-- css 
    |     |   |-- styles.min.css
    |     |   |-- vendors.min.css
    |     |-- js
    |     |   |-- main.min.js
    |     |   |-- vendors.min.js
```


- `styles.min.css` file contain all custom css and `vendors.min.css` contain all plugins css.
- `main.min.js` file contain all custom js and `vendors.min.js` contain all plugins js.


!> When you will upload your project on live server. than you should upload this **dist** folder for better performance


#### remove or clean **`dist`** folder

When you run `gulp clean` then your **dist** folder automatically remove
  
```bash
    gulp clean
```








