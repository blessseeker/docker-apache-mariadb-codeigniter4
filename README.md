<h1>What is This?</h1>
<p>This is a starter project for <strong>Codeigniter 4</strong> with <strong>docker</strong>, using <strong>php7.4-apache</strong> base image as web server and <strong>mariadb</strong> as database server.</p>
<h1>How to Use This?</h1>
<p>After cloning or downloading this repository, go to root folder of this project and run <code>docker build -t dockerci4:v1.0 .</code> (You can use any different image name and its tagname as you like, just keep in mind that you also have to change image name on <strong>docker-compose.yml</strong> file). This command will create image based on the <strong>Dockerfile</strong>, using <strong>php7.4-apache</strong> base image</p>
<p>Next thing you have to do is to set up the <code>.env</code>. This file will replace the existing <code>.env</code> on the image we built before. If you are wondering to set this file up, you can find it on <a href="https://codeigniter4.github.io/userguide/general/configuration.html">Codeigniter 4 documentation</a>.</p>
<p>If you are already confident with your <code>.env</code> file, you have to run <code>docker-compose up -d</code> in order to get your application up and running.</p>
