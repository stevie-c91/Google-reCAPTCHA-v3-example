## Google reCAPTCHA v3 example

A simple contact form, using [Google reCAPTCHA v3](https://developers.google.com/recaptcha/docs/v3) with PHP for server side validation.

Add your Site key from the reCAPTCHA dashboard on lines 9 and 12 of 'public/index.php':

<pre><code>YOUR_RECAPTCHA_SITE_KEY</code></pre>

Add your Secret key from the reCAPTCHA dashboard on line 31 of 'public/index.php':

<pre><code>YOUR_RECAPTCHA_SECRET_KEY</code></pre>

This can be run locally with <code>vagrant up</code>.


You should run the following to install the required Vagrant plugins:

<pre><code>$ vagrant plugin install vagrant-hostmanager</code></pre>

Access the website locally at http://recaptcha.local

The Vagrant box being used is [Scotchbox Pro](https://box.scotch.io/pro)

See blog post [here](https://stevencotterill.co.uk/blog/adding-google-recaptcha-v3-to-a-php-form)

![reCAPTCHA v3 form](https://stevencotterill.co.uk/img/github-recaptcha-form.jpg)