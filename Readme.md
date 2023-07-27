# Online voting system
<h2>Introduction</h2>
<h2>Table of Contents</h2>

<h2 id="setup">Setup</h2>
<p>In order to run the project locally, you must have node and npm installed globally.</p>
<h3>Step 1</h3>
Clone the project and install dependencies in both frontend and backend directory.

Include a `.env` file in the `server` directory with the following environment variables.

```
PORT = 4000
DATABASE = 'mongodb://localhost/<DATABASE_NAME>'
SECRET = 'ThisIsATemporarySecretKey'
```
```
https://github.com/samartha5611/Online-voting-system.git
cd /client && npm install
cd ../
cd /server && npm install
```

<h3>Step 2</h3>

```
chmod +x start.sh
bash start.sh
```


<h3>client</h3>
<ul>
<li><b>build</b>: Base directory for the live version. It gets updated when you run "npm run build"</li>
<li><b>public</b>: index.html and template page.</li>
<li><b>src</b>: JavaScript entry point and it is where all the logic lives.</li>
<li><b>components</b>: Presentational and dynamic react components.</li>

<li><b>redux</b>: Redux related logic (global state management).</li>
</ul>

<h3>server</h3>
<ul>
<li><b>Index.js</b>: Entry point.</li>
</ul>

<h2 id="tech">Tech Stack</h2>

![MERN](https://blog.hyperiondev.com/wp-content/uploads/2018/09/Blog-Article-MERN-Stack.jpg)
