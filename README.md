What is Serve?
=============

Serve is an open-source rapid prototyping framework for Web applications. It makes it easy to prototype functionality without writing a single line of backend code.


How do I install and run Serve?
-------------------------------

Serve and other components are all Ruby gems. Serve is distributed as a Ruby gem to make it easy to get up and running. You must have Ruby installed in order to download and use Serve. The Ruby download page provides instructions for getting Ruby setup on different platforms:

<http://www.ruby-lang.org/en/downloads/>

After you have Ruby installed, you will need to install bundler:

    gem install bundler

(OSX and Unix users may need to prefix the command with `sudo`.)

Bundler allows your project to specify what gems are needed and at what version. This allows consistancy between deployed locations.

<http://gembundler.com/>

After you have bundler, and you are in your projects folder, have bundler install your gems:

	bundle install

After Serve and other gems are installed, you can start it up in your directory like this:

    serve

This will start Serve on port 4000. You can now view the prototype in your Web browser at this URL:

<http://localhost:4000>


Compass and Sass
----------------

This prototype uses Compass and Sass to generate CSS.

Learn more about Sass:

<http://sass-lang.org>

Learn more about Compass:

<http://compass-style.org>


Rack and Passenger
------------------

Astute users may notice that this project is also a simple Rack application. This means that it is easy to deploy it on Passenger or in any other Rack-friendly environment. Rack it up with the `rackup` command. For more information about using Serve and Passenger see:

<http://bit.ly/serve-and-passenger>


Exporting
---------

To export this project to pure HTML and CSS you will need the prerelease version of Serve. To get started with the prerelease version:

    gem install --pre serve

To export your project, use the new "export" command:

    serve export <project>:<output>

Where "project" is the path to the project and "output" is the path to the directory where you would like your HTML and CSS generated.


Learning Serve
-------------

You can learn more about Serve on the GitHub project page:

<http://github.com/jlong/serve>
