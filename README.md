## README

This is a Rails 4 template with PostgreSQL, Heroku, the Foundation template and Thoughtbot's clearance authentication already working.

It is based on the Heroku guide for Rails 4:

https://devcenter.heroku.com/articles/getting-started-with-rails4

## How to use this / What you have to do

* Change AppName to your name
* Update config/database.yml
* Install dependencies
```no-highlight
bundle install
```
* Create databases: 
```no-highlight
rake db:create:all
```
* Migrate databases: 
```no-highlight
rake db:migrate
```
* Update secure secret hash
```no-highlight
rake secret
```

## Based on

Clearance - Rails authentication with email & password.

https://github.com/thoughtbot/clearance

Foundation for Rails

https://github.com/zurb/foundation-rails

## License

The MIT License (Rails, Clearance, this compilation)

```
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
