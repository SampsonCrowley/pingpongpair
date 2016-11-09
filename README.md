# Pingpongpairing

## Installation

requires ngrok to be installed
[advanced user tunneling made easy](https://ngrok.com/download)

clone this repo into your project folder

```git
git clone https://github.com/SampsonCrowley/pingpongpair.git
```

cd into the pingpongpair dir:

    $ cd pingpongpair

run ./setup:

    $ ./setup

delete the pingpongpair dir. you don't need it now

    $ cd ..
    $ rm -r pingpongpair

run the pingpong executable

    $ exe/pingpong

in Guardfile change the url in line 20 to your pair's ngrok URL

  `bundle exec exe/sendevent **"http://localhost:5000"** #{m[0]}`

to:

  `bundle exec exe/sendevent **http://27aa2ed0.ngrok.io** #{m[0]}`


## To Stop the servers

    $ press ctrl^c until you are bash at your bash line

## Important Notes

The "ping" a.k.a. test writer should write tests in the pair folder.
files will added to the Test Writer's spec folder on demand

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/pingpongpairing.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

