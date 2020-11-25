# Atrium Demo

This is a simple demo application that showcases how one might integrate MX's connect widget within your web app. You can use this and the [docs](https://atrium.mx.com/docs#mx-connect-widget) together.

## Quick start
Clone the project and serve up `index.html` with whatever server you like.

  Ruby one liner:

  ```ruby
  ruby -rwebrick -e 'WEBrick::HTTPServer.new(:Port => 8000, :DocumentRoot => Dir.pwd).start'
  ```

  Navigate to `localhost:8000/atrium.html`


Next you need a connect widget URL. Documentation to get that is [here](https://atrium.mx.com/docs#get-a-url). Once you have a URL, enter it in the input field and hit the `Open Connect` button.
