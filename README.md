# Skeleton base project
Base skeleton package structure with gradle.


####Project package structure

    |- Domain-name(i.e Customer)
        |- config 
        |- domain
            |- entity
            |- exceptions
            |- repository
            |- service
                |- impl
        |- infrastructure
            |- entrypoints
                |- kafka
                |- rabbit
                |- rest
                    |- exceptions
                    |- V{X}
                       |- advice
                       |- json
                       |- mapper 
            |- repository
                |- exceptions
                |- jpa
                |- kafka
                |- rabbit
                |- mapper
                |- model
                |- rest

[![Build Status](http://img.shields.io/travis/badges/badgerbadgerbadger.svg?style=flat-square)](https://travis-ci.org/badges/badgerbadgerbadger) [![Coverage Status](http://img.shields.io/coveralls/badges/badgerbadgerbadger.svg?style=flat-square)](https://coveralls.io/r/badges/badgerbadgerbadger) [![Gem Version](http://img.shields.io/gem/v/badgerbadgerbadger.svg?style=flat-square)](https://rubygems.org/gems/badgerbadgerbadger)  
## License
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)
- **[MIT license](http://opensource.org/licenses/mit-license.php)**