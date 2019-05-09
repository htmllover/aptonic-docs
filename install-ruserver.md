### Install and Run Local Server

After unzip download folder you will get two folder inside it
- **Aptonic** (This is your project folder)
- **Documentation**

```bash
cd path/Aptonic
```
Once done, you need to install the project dependencies with `npm`, that we previously installed. Enter the following command at the root of the `Aptonic` folder :


```bash
npm install
```

This will automatically fecth all the dependencies listed in your `package.json` file for the Aptonic. This will also install them in your project (in a newly created directory named `node_modules`). Once the installation process is done, you are ready to run your project and begin developing or customizing.  
 
#### Run Server

After install process now you can run local server-

**For run server** use this commend then automatically run your local server and open default browser in this port `http://localhost:3000`
```bash
gulp default
```
Now you can customize or update real content. then you can see the change on your browser live preview. 
However, before you start we are going to take a closer look to the template structure, and to how things are organized.






















