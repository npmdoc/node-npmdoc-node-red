# api documentation for  [node-red (v0.16.2)](http://nodered.org)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-red.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-red) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-red.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-red)
#### A visual tool for wiring the Internet of Things

[![NPM](https://nodei.co/npm/node-red.png?downloads=true)](https://www.npmjs.com/package/node-red)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-red/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-node-red_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-red/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-red/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-red/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "node-red": "./red.js",
        "node-red-pi": "bin/node-red-pi"
    },
    "bugs": {
        "url": "https://github.com/node-red/node-red/issues"
    },
    "contributors": [
        {
            "name": "Nick O'Leary"
        },
        {
            "name": "Dave Conway-Jones"
        }
    ],
    "dependencies": {
        "basic-auth": "1.1.0",
        "bcrypt": "~1.0.1",
        "bcryptjs": "2.4.0",
        "body-parser": "1.15.2",
        "cheerio": "0.22.0",
        "clone": "2.1.0",
        "cookie-parser": "1.4.3",
        "cors": "2.8.1",
        "cron": "1.2.1",
        "express": "4.14.0",
        "follow-redirects": "1.2.1",
        "fs-extra": "1.0.0",
        "fs.notify": "0.0.4",
        "i18next": "1.10.6",
        "is-utf8": "0.2.1",
        "js-yaml": "3.7.0",
        "json-stringify-safe": "5.0.1",
        "jsonata": "1.0.10",
        "media-typer": "0.3.0",
        "mqtt": "2.2.1",
        "mustache": "2.3.0",
        "node-red-node-email": "0.1.*",
        "node-red-node-feedparser": "0.1.*",
        "node-red-node-rbe": "0.1.*",
        "node-red-node-twitter": "0.1.*",
        "nopt": "3.0.6",
        "oauth2orize": "1.7.0",
        "on-headers": "1.0.1",
        "passport": "0.3.2",
        "passport-http-bearer": "1.0.1",
        "passport-oauth2-client-password": "0.1.2",
        "raw-body": "2.2.0",
        "semver": "5.3.0",
        "sentiment": "2.1.0",
        "uglify-js": "2.7.5",
        "when": "3.7.7",
        "ws": "1.1.1",
        "xml2js": "0.4.17"
    },
    "description": "A visual tool for wiring the Internet of Things",
    "devDependencies": {
        "grunt": "~1.0.1",
        "grunt-chmod": "~1.1.1",
        "grunt-cli": "~1.2.0",
        "grunt-concurrent": "~2.3.1",
        "grunt-contrib-clean": "~1.0.0",
        "grunt-contrib-compress": "~1.3.0",
        "grunt-contrib-concat": "~1.0.1",
        "grunt-contrib-copy": "~1.0.0",
        "grunt-contrib-jshint": "~1.1.0",
        "grunt-contrib-uglify": "~2.0.0",
        "grunt-contrib-watch": "~1.0.0",
        "grunt-jsonlint": "~1.1.0",
        "grunt-nodemon": "~0.4.2",
        "grunt-sass": "~1.2.1",
        "grunt-simple-mocha": "~0.4.1",
        "mocha": "~3.2.0",
        "should": "^8.4.0",
        "sinon": "1.17.7",
        "supertest": "2.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "3f77d608f1b0e89907af3f31e2c3eb8844a2b17b",
        "tarball": "https://registry.npmjs.org/node-red/-/node-red-0.16.2.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "homepage": "http://nodered.org",
    "keywords": [
        "editor",
        "messaging",
        "iot",
        "flow"
    ],
    "license": "Apache-2.0",
    "main": "red/red.js",
    "maintainers": [
        {
            "name": "dceejay",
            "email": "ceejay@vnet.ibm.com"
        },
        {
            "name": "knolleary",
            "email": "nick.oleary@gmail.com"
        }
    ],
    "name": "node-red",
    "optionalDependencies": {
        "bcrypt": "~1.0.1"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/node-red/node-red.git"
    },
    "scripts": {
        "build": "grunt build",
        "start": "node red.js",
        "test": "grunt"
    },
    "version": "0.16.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module node-red](#apidoc.module.node-red)
1.  [function <span class="apidocSignatureSpan">node-red.</span>httpAdmin (req, res, next)](#apidoc.element.node-red.httpAdmin)
1.  [function <span class="apidocSignatureSpan">node-red.</span>httpAdmin.parent (req, res, next)](#apidoc.element.node-red.httpAdmin.parent)
1.  [function <span class="apidocSignatureSpan">node-red.</span>httpNode (req, res, next)](#apidoc.element.node-red.httpNode)
1.  [function <span class="apidocSignatureSpan">node-red.</span>init (httpServer, userSettings)](#apidoc.element.node-red.init)
1.  [function <span class="apidocSignatureSpan">node-red.</span>start ()](#apidoc.element.node-red.start)
1.  [function <span class="apidocSignatureSpan">node-red.</span>stop ()](#apidoc.element.node-red.stop)
1.  [function <span class="apidocSignatureSpan">node-red.</span>version ()](#apidoc.element.node-red.version)
1.  object <span class="apidocSignatureSpan">node-red.</span>auth
1.  object <span class="apidocSignatureSpan">node-red.</span>comms
1.  object <span class="apidocSignatureSpan">node-red.</span>httpAdmin._events
1.  object <span class="apidocSignatureSpan">node-red.</span>httpAdmin.request
1.  object <span class="apidocSignatureSpan">node-red.</span>httpAdmin.response
1.  object <span class="apidocSignatureSpan">node-red.</span>httpAdmin.settings
1.  object <span class="apidocSignatureSpan">node-red.</span>httpAdmin.settings.view.prototype
1.  object <span class="apidocSignatureSpan">node-red.</span>httpNode._events
1.  object <span class="apidocSignatureSpan">node-red.</span>httpNode.request
1.  object <span class="apidocSignatureSpan">node-red.</span>httpNode.response
1.  object <span class="apidocSignatureSpan">node-red.</span>httpNode.settings
1.  object <span class="apidocSignatureSpan">node-red.</span>library
1.  object <span class="apidocSignatureSpan">node-red.</span>log
1.  object <span class="apidocSignatureSpan">node-red.</span>nodes
1.  object <span class="apidocSignatureSpan">node-red.</span>server
1.  object <span class="apidocSignatureSpan">node-red.</span>settings
1.  object <span class="apidocSignatureSpan">node-red.</span>settings.functionGlobalContext
1.  object <span class="apidocSignatureSpan">node-red.</span>util

#### [module node-red.auth](#apidoc.module.node-red.auth)
1.  [function <span class="apidocSignatureSpan">node-red.auth.</span>needsPermission (permission)](#apidoc.element.node-red.auth.needsPermission)

#### [module node-red.comms](#apidoc.module.node-red.comms)
1.  [function <span class="apidocSignatureSpan">node-red.comms.</span>publish (topic, data, retain)](#apidoc.element.node-red.comms.publish)

#### [module node-red.httpAdmin](#apidoc.module.node-red.httpAdmin)
1.  [function <span class="apidocSignatureSpan">node-red.</span>httpAdmin (req, res, next)](#apidoc.element.node-red.httpAdmin.httpAdmin)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>_router (req, res, next)](#apidoc.element.node-red.httpAdmin._router)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>acl (path)](#apidoc.element.node-red.httpAdmin.acl)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>addListener (type, listener)](#apidoc.element.node-red.httpAdmin.addListener)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>all (path)](#apidoc.element.node-red.httpAdmin.all)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>bind (path)](#apidoc.element.node-red.httpAdmin.bind)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>checkout (path)](#apidoc.element.node-red.httpAdmin.checkout)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>connect (path)](#apidoc.element.node-red.httpAdmin.connect)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>copy (path)](#apidoc.element.node-red.httpAdmin.copy)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>defaultConfiguration ()](#apidoc.element.node-red.httpAdmin.defaultConfiguration)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>del (arg0)](#apidoc.element.node-red.httpAdmin.del)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>delete (path)](#apidoc.element.node-red.httpAdmin.delete)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>disable (setting)](#apidoc.element.node-red.httpAdmin.disable)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>disabled (setting)](#apidoc.element.node-red.httpAdmin.disabled)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>emit (type)](#apidoc.element.node-red.httpAdmin.emit)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>enable (setting)](#apidoc.element.node-red.httpAdmin.enable)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>enabled (setting)](#apidoc.element.node-red.httpAdmin.enabled)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>engine (ext, fn)](#apidoc.element.node-red.httpAdmin.engine)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>eventNames ()](#apidoc.element.node-red.httpAdmin.eventNames)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>get (path)](#apidoc.element.node-red.httpAdmin.get)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>getMaxListeners ()](#apidoc.element.node-red.httpAdmin.getMaxListeners)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>handle (req, res, callback)](#apidoc.element.node-red.httpAdmin.handle)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>head (path)](#apidoc.element.node-red.httpAdmin.head)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>init ()](#apidoc.element.node-red.httpAdmin.init)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>lazyrouter ()](#apidoc.element.node-red.httpAdmin.lazyrouter)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>link (path)](#apidoc.element.node-red.httpAdmin.link)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>listen ()](#apidoc.element.node-red.httpAdmin.listen)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>listenerCount (type)](#apidoc.element.node-red.httpAdmin.listenerCount)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>listeners (type)](#apidoc.element.node-red.httpAdmin.listeners)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>lock (path)](#apidoc.element.node-red.httpAdmin.lock)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>m-search (path)](#apidoc.element.node-red.httpAdmin.m-search)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>merge (path)](#apidoc.element.node-red.httpAdmin.merge)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>mkactivity (path)](#apidoc.element.node-red.httpAdmin.mkactivity)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>mkcalendar (path)](#apidoc.element.node-red.httpAdmin.mkcalendar)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>mkcol (path)](#apidoc.element.node-red.httpAdmin.mkcol)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>move (path)](#apidoc.element.node-red.httpAdmin.move)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>notify (path)](#apidoc.element.node-red.httpAdmin.notify)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>on (type, listener)](#apidoc.element.node-red.httpAdmin.on)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>once (type, listener)](#apidoc.element.node-red.httpAdmin.once)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>options (path)](#apidoc.element.node-red.httpAdmin.options)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>param (name, fn)](#apidoc.element.node-red.httpAdmin.param)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>parent (req, res, next)](#apidoc.element.node-red.httpAdmin.parent)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>patch (path)](#apidoc.element.node-red.httpAdmin.patch)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>path ()](#apidoc.element.node-red.httpAdmin.path)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>post (path)](#apidoc.element.node-red.httpAdmin.post)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>prependListener (type, listener)](#apidoc.element.node-red.httpAdmin.prependListener)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>prependOnceListener (type, listener)](#apidoc.element.node-red.httpAdmin.prependOnceListener)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>propfind (path)](#apidoc.element.node-red.httpAdmin.propfind)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>proppatch (path)](#apidoc.element.node-red.httpAdmin.proppatch)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>purge (path)](#apidoc.element.node-red.httpAdmin.purge)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>put (path)](#apidoc.element.node-red.httpAdmin.put)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>rebind (path)](#apidoc.element.node-red.httpAdmin.rebind)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>removeAllListeners (type)](#apidoc.element.node-red.httpAdmin.removeAllListeners)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>removeListener (type, listener)](#apidoc.element.node-red.httpAdmin.removeListener)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>render (name, options, callback)](#apidoc.element.node-red.httpAdmin.render)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>report (path)](#apidoc.element.node-red.httpAdmin.report)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>route (path)](#apidoc.element.node-red.httpAdmin.route)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>search (path)](#apidoc.element.node-red.httpAdmin.search)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>set (setting, val)](#apidoc.element.node-red.httpAdmin.set)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>setMaxListeners (n)](#apidoc.element.node-red.httpAdmin.setMaxListeners)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>subscribe (path)](#apidoc.element.node-red.httpAdmin.subscribe)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>trace (path)](#apidoc.element.node-red.httpAdmin.trace)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>unbind (path)](#apidoc.element.node-red.httpAdmin.unbind)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>unlink (path)](#apidoc.element.node-red.httpAdmin.unlink)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>unlock (path)](#apidoc.element.node-red.httpAdmin.unlock)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>unsubscribe (path)](#apidoc.element.node-red.httpAdmin.unsubscribe)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>use (fn)](#apidoc.element.node-red.httpAdmin.use)
1.  number <span class="apidocSignatureSpan">node-red.httpAdmin.</span>_eventsCount
1.  object <span class="apidocSignatureSpan">node-red.httpAdmin.</span>_events
1.  object <span class="apidocSignatureSpan">node-red.httpAdmin.</span>cache
1.  object <span class="apidocSignatureSpan">node-red.httpAdmin.</span>engines
1.  object <span class="apidocSignatureSpan">node-red.httpAdmin.</span>locals
1.  object <span class="apidocSignatureSpan">node-red.httpAdmin.</span>request
1.  object <span class="apidocSignatureSpan">node-red.httpAdmin.</span>response
1.  object <span class="apidocSignatureSpan">node-red.httpAdmin.</span>settings
1.  string <span class="apidocSignatureSpan">node-red.httpAdmin.</span>mountpath
1.  undefined <span class="apidocSignatureSpan">node-red.httpAdmin.</span>domain

#### [module node-red.httpAdmin._events](#apidoc.module.node-red.httpAdmin._events)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin._events.</span>mount (parent)](#apidoc.element.node-red.httpAdmin._events.mount)

#### [module node-red.httpAdmin.parent](#apidoc.module.node-red.httpAdmin.parent)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>parent (req, res, next)](#apidoc.element.node-red.httpAdmin.parent.parent)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>_router (req, res, next)](#apidoc.element.node-red.httpAdmin.parent._router)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>acl (path)](#apidoc.element.node-red.httpAdmin.parent.acl)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>addListener (type, listener)](#apidoc.element.node-red.httpAdmin.parent.addListener)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>all (path)](#apidoc.element.node-red.httpAdmin.parent.all)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>bind (path)](#apidoc.element.node-red.httpAdmin.parent.bind)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>checkout (path)](#apidoc.element.node-red.httpAdmin.parent.checkout)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>connect (path)](#apidoc.element.node-red.httpAdmin.parent.connect)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>copy (path)](#apidoc.element.node-red.httpAdmin.parent.copy)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>defaultConfiguration ()](#apidoc.element.node-red.httpAdmin.parent.defaultConfiguration)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>del (arg0)](#apidoc.element.node-red.httpAdmin.parent.del)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>delete (path)](#apidoc.element.node-red.httpAdmin.parent.delete)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>disable (setting)](#apidoc.element.node-red.httpAdmin.parent.disable)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>disabled (setting)](#apidoc.element.node-red.httpAdmin.parent.disabled)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>emit (type)](#apidoc.element.node-red.httpAdmin.parent.emit)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>enable (setting)](#apidoc.element.node-red.httpAdmin.parent.enable)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>enabled (setting)](#apidoc.element.node-red.httpAdmin.parent.enabled)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>engine (ext, fn)](#apidoc.element.node-red.httpAdmin.parent.engine)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>eventNames ()](#apidoc.element.node-red.httpAdmin.parent.eventNames)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>get (path)](#apidoc.element.node-red.httpAdmin.parent.get)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>getMaxListeners ()](#apidoc.element.node-red.httpAdmin.parent.getMaxListeners)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>handle (req, res, callback)](#apidoc.element.node-red.httpAdmin.parent.handle)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>head (path)](#apidoc.element.node-red.httpAdmin.parent.head)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>init ()](#apidoc.element.node-red.httpAdmin.parent.init)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>lazyrouter ()](#apidoc.element.node-red.httpAdmin.parent.lazyrouter)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>link (path)](#apidoc.element.node-red.httpAdmin.parent.link)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>listen ()](#apidoc.element.node-red.httpAdmin.parent.listen)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>listenerCount (type)](#apidoc.element.node-red.httpAdmin.parent.listenerCount)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>listeners (type)](#apidoc.element.node-red.httpAdmin.parent.listeners)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>lock (path)](#apidoc.element.node-red.httpAdmin.parent.lock)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>m-search (path)](#apidoc.element.node-red.httpAdmin.parent.m-search)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>merge (path)](#apidoc.element.node-red.httpAdmin.parent.merge)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>mkactivity (path)](#apidoc.element.node-red.httpAdmin.parent.mkactivity)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>mkcalendar (path)](#apidoc.element.node-red.httpAdmin.parent.mkcalendar)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>mkcol (path)](#apidoc.element.node-red.httpAdmin.parent.mkcol)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>move (path)](#apidoc.element.node-red.httpAdmin.parent.move)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>notify (path)](#apidoc.element.node-red.httpAdmin.parent.notify)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>on (type, listener)](#apidoc.element.node-red.httpAdmin.parent.on)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>once (type, listener)](#apidoc.element.node-red.httpAdmin.parent.once)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>options (path)](#apidoc.element.node-red.httpAdmin.parent.options)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>param (name, fn)](#apidoc.element.node-red.httpAdmin.parent.param)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>patch (path)](#apidoc.element.node-red.httpAdmin.parent.patch)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>path ()](#apidoc.element.node-red.httpAdmin.parent.path)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>post (path)](#apidoc.element.node-red.httpAdmin.parent.post)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>prependListener (type, listener)](#apidoc.element.node-red.httpAdmin.parent.prependListener)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>prependOnceListener (type, listener)](#apidoc.element.node-red.httpAdmin.parent.prependOnceListener)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>propfind (path)](#apidoc.element.node-red.httpAdmin.parent.propfind)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>proppatch (path)](#apidoc.element.node-red.httpAdmin.parent.proppatch)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>purge (path)](#apidoc.element.node-red.httpAdmin.parent.purge)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>put (path)](#apidoc.element.node-red.httpAdmin.parent.put)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>rebind (path)](#apidoc.element.node-red.httpAdmin.parent.rebind)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>removeAllListeners (type)](#apidoc.element.node-red.httpAdmin.parent.removeAllListeners)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>removeListener (type, listener)](#apidoc.element.node-red.httpAdmin.parent.removeListener)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>render (name, options, callback)](#apidoc.element.node-red.httpAdmin.parent.render)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>report (path)](#apidoc.element.node-red.httpAdmin.parent.report)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>route (path)](#apidoc.element.node-red.httpAdmin.parent.route)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>search (path)](#apidoc.element.node-red.httpAdmin.parent.search)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>set (setting, val)](#apidoc.element.node-red.httpAdmin.parent.set)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>setMaxListeners (n)](#apidoc.element.node-red.httpAdmin.parent.setMaxListeners)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>subscribe (path)](#apidoc.element.node-red.httpAdmin.parent.subscribe)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>trace (path)](#apidoc.element.node-red.httpAdmin.parent.trace)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>unbind (path)](#apidoc.element.node-red.httpAdmin.parent.unbind)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>unlink (path)](#apidoc.element.node-red.httpAdmin.parent.unlink)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>unlock (path)](#apidoc.element.node-red.httpAdmin.parent.unlock)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>unsubscribe (path)](#apidoc.element.node-red.httpAdmin.parent.unsubscribe)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>use (fn)](#apidoc.element.node-red.httpAdmin.parent.use)
1.  number <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>_eventsCount
1.  object <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>_events
1.  object <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>cache
1.  object <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>engines
1.  object <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>locals
1.  object <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>request
1.  object <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>response
1.  object <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>settings
1.  string <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>mountpath
1.  undefined <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>domain

#### [module node-red.httpAdmin.request](#apidoc.module.node-red.httpAdmin.request)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.request.</span>app (req, res, next)](#apidoc.element.node-red.httpAdmin.request.app)

#### [module node-red.httpAdmin.response](#apidoc.module.node-red.httpAdmin.response)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.response.</span>app (req, res, next)](#apidoc.element.node-red.httpAdmin.response.app)

#### [module node-red.httpAdmin.settings](#apidoc.module.node-red.httpAdmin.settings)
1.  boolean <span class="apidocSignatureSpan">node-red.httpAdmin.settings.</span>x-powered-by
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.settings.</span>view (name, options)](#apidoc.element.node-red.httpAdmin.settings.view)
1.  string <span class="apidocSignatureSpan">node-red.httpAdmin.settings.</span>env
1.  string <span class="apidocSignatureSpan">node-red.httpAdmin.settings.</span>etag
1.  string <span class="apidocSignatureSpan">node-red.httpAdmin.settings.</span>views

#### [module node-red.httpAdmin.settings.view.prototype](#apidoc.module.node-red.httpAdmin.settings.view.prototype)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.settings.view.prototype.</span>lookup (name)](#apidoc.element.node-red.httpAdmin.settings.view.prototype.lookup)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.settings.view.prototype.</span>render (options, callback)](#apidoc.element.node-red.httpAdmin.settings.view.prototype.render)
1.  [function <span class="apidocSignatureSpan">node-red.httpAdmin.settings.view.prototype.</span>resolve (dir, file)](#apidoc.element.node-red.httpAdmin.settings.view.prototype.resolve)

#### [module node-red.httpNode](#apidoc.module.node-red.httpNode)
1.  [function <span class="apidocSignatureSpan">node-red.</span>httpNode (req, res, next)](#apidoc.element.node-red.httpNode.httpNode)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>acl (path)](#apidoc.element.node-red.httpNode.acl)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>addListener (type, listener)](#apidoc.element.node-red.httpNode.addListener)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>all (path)](#apidoc.element.node-red.httpNode.all)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>bind (path)](#apidoc.element.node-red.httpNode.bind)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>checkout (path)](#apidoc.element.node-red.httpNode.checkout)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>connect (path)](#apidoc.element.node-red.httpNode.connect)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>copy (path)](#apidoc.element.node-red.httpNode.copy)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>defaultConfiguration ()](#apidoc.element.node-red.httpNode.defaultConfiguration)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>del (arg0)](#apidoc.element.node-red.httpNode.del)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>delete (path)](#apidoc.element.node-red.httpNode.delete)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>disable (setting)](#apidoc.element.node-red.httpNode.disable)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>disabled (setting)](#apidoc.element.node-red.httpNode.disabled)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>emit (type)](#apidoc.element.node-red.httpNode.emit)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>enable (setting)](#apidoc.element.node-red.httpNode.enable)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>enabled (setting)](#apidoc.element.node-red.httpNode.enabled)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>engine (ext, fn)](#apidoc.element.node-red.httpNode.engine)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>eventNames ()](#apidoc.element.node-red.httpNode.eventNames)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>get (path)](#apidoc.element.node-red.httpNode.get)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>getMaxListeners ()](#apidoc.element.node-red.httpNode.getMaxListeners)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>handle (req, res, callback)](#apidoc.element.node-red.httpNode.handle)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>head (path)](#apidoc.element.node-red.httpNode.head)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>init ()](#apidoc.element.node-red.httpNode.init)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>lazyrouter ()](#apidoc.element.node-red.httpNode.lazyrouter)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>link (path)](#apidoc.element.node-red.httpNode.link)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>listen ()](#apidoc.element.node-red.httpNode.listen)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>listenerCount (type)](#apidoc.element.node-red.httpNode.listenerCount)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>listeners (type)](#apidoc.element.node-red.httpNode.listeners)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>lock (path)](#apidoc.element.node-red.httpNode.lock)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>m-search (path)](#apidoc.element.node-red.httpNode.m-search)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>merge (path)](#apidoc.element.node-red.httpNode.merge)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>mkactivity (path)](#apidoc.element.node-red.httpNode.mkactivity)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>mkcalendar (path)](#apidoc.element.node-red.httpNode.mkcalendar)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>mkcol (path)](#apidoc.element.node-red.httpNode.mkcol)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>move (path)](#apidoc.element.node-red.httpNode.move)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>notify (path)](#apidoc.element.node-red.httpNode.notify)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>on (type, listener)](#apidoc.element.node-red.httpNode.on)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>once (type, listener)](#apidoc.element.node-red.httpNode.once)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>options (path)](#apidoc.element.node-red.httpNode.options)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>param (name, fn)](#apidoc.element.node-red.httpNode.param)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>parent (req, res, next)](#apidoc.element.node-red.httpNode.parent)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>patch (path)](#apidoc.element.node-red.httpNode.patch)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>path ()](#apidoc.element.node-red.httpNode.path)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>post (path)](#apidoc.element.node-red.httpNode.post)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>prependListener (type, listener)](#apidoc.element.node-red.httpNode.prependListener)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>prependOnceListener (type, listener)](#apidoc.element.node-red.httpNode.prependOnceListener)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>propfind (path)](#apidoc.element.node-red.httpNode.propfind)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>proppatch (path)](#apidoc.element.node-red.httpNode.proppatch)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>purge (path)](#apidoc.element.node-red.httpNode.purge)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>put (path)](#apidoc.element.node-red.httpNode.put)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>rebind (path)](#apidoc.element.node-red.httpNode.rebind)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>removeAllListeners (type)](#apidoc.element.node-red.httpNode.removeAllListeners)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>removeListener (type, listener)](#apidoc.element.node-red.httpNode.removeListener)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>render (name, options, callback)](#apidoc.element.node-red.httpNode.render)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>report (path)](#apidoc.element.node-red.httpNode.report)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>route (path)](#apidoc.element.node-red.httpNode.route)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>search (path)](#apidoc.element.node-red.httpNode.search)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>set (setting, val)](#apidoc.element.node-red.httpNode.set)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>setMaxListeners (n)](#apidoc.element.node-red.httpNode.setMaxListeners)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>subscribe (path)](#apidoc.element.node-red.httpNode.subscribe)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>trace (path)](#apidoc.element.node-red.httpNode.trace)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>unbind (path)](#apidoc.element.node-red.httpNode.unbind)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>unlink (path)](#apidoc.element.node-red.httpNode.unlink)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>unlock (path)](#apidoc.element.node-red.httpNode.unlock)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>unsubscribe (path)](#apidoc.element.node-red.httpNode.unsubscribe)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.</span>use (fn)](#apidoc.element.node-red.httpNode.use)
1.  number <span class="apidocSignatureSpan">node-red.httpNode.</span>_eventsCount
1.  object <span class="apidocSignatureSpan">node-red.httpNode.</span>_events
1.  object <span class="apidocSignatureSpan">node-red.httpNode.</span>cache
1.  object <span class="apidocSignatureSpan">node-red.httpNode.</span>engines
1.  object <span class="apidocSignatureSpan">node-red.httpNode.</span>locals
1.  object <span class="apidocSignatureSpan">node-red.httpNode.</span>request
1.  object <span class="apidocSignatureSpan">node-red.httpNode.</span>response
1.  object <span class="apidocSignatureSpan">node-red.httpNode.</span>settings
1.  string <span class="apidocSignatureSpan">node-red.httpNode.</span>mountpath
1.  undefined <span class="apidocSignatureSpan">node-red.httpNode.</span>domain

#### [module node-red.httpNode._events](#apidoc.module.node-red.httpNode._events)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode._events.</span>mount (parent)](#apidoc.element.node-red.httpNode._events.mount)

#### [module node-red.httpNode.request](#apidoc.module.node-red.httpNode.request)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.request.</span>app (req, res, next)](#apidoc.element.node-red.httpNode.request.app)

#### [module node-red.httpNode.response](#apidoc.module.node-red.httpNode.response)
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.response.</span>app (req, res, next)](#apidoc.element.node-red.httpNode.response.app)

#### [module node-red.httpNode.settings](#apidoc.module.node-red.httpNode.settings)
1.  boolean <span class="apidocSignatureSpan">node-red.httpNode.settings.</span>x-powered-by
1.  [function <span class="apidocSignatureSpan">node-red.httpNode.settings.</span>view (name, options)](#apidoc.element.node-red.httpNode.settings.view)
1.  string <span class="apidocSignatureSpan">node-red.httpNode.settings.</span>env
1.  string <span class="apidocSignatureSpan">node-red.httpNode.settings.</span>etag
1.  string <span class="apidocSignatureSpan">node-red.httpNode.settings.</span>views

#### [module node-red.library](#apidoc.module.node-red.library)
1.  [function <span class="apidocSignatureSpan">node-red.library.</span>register (type)](#apidoc.element.node-red.library.register)

#### [module node-red.log](#apidoc.module.node-red.log)
1.  [function <span class="apidocSignatureSpan">node-red.</span>log (msg)](#apidoc.element.node-red.log.log)
1.  [function <span class="apidocSignatureSpan">node-red.log.</span>_ ()](#apidoc.element.node-red.log._)
1.  [function <span class="apidocSignatureSpan">node-red.log.</span>addHandler (func)](#apidoc.element.node-red.log.addHandler)
1.  [function <span class="apidocSignatureSpan">node-red.log.</span>audit (msg, req)](#apidoc.element.node-red.log.audit)
1.  [function <span class="apidocSignatureSpan">node-red.log.</span>debug (msg)](#apidoc.element.node-red.log.debug)
1.  [function <span class="apidocSignatureSpan">node-red.log.</span>error (msg)](#apidoc.element.node-red.log.error)
1.  [function <span class="apidocSignatureSpan">node-red.log.</span>info (msg)](#apidoc.element.node-red.log.info)
1.  [function <span class="apidocSignatureSpan">node-red.log.</span>init (settings)](#apidoc.element.node-red.log.init)
1.  [function <span class="apidocSignatureSpan">node-red.log.</span>metric ()](#apidoc.element.node-red.log.metric)
1.  [function <span class="apidocSignatureSpan">node-red.log.</span>removeHandler (func)](#apidoc.element.node-red.log.removeHandler)
1.  [function <span class="apidocSignatureSpan">node-red.log.</span>trace (msg)](#apidoc.element.node-red.log.trace)
1.  [function <span class="apidocSignatureSpan">node-red.log.</span>warn (msg)](#apidoc.element.node-red.log.warn)
1.  number <span class="apidocSignatureSpan">node-red.log.</span>AUDIT
1.  number <span class="apidocSignatureSpan">node-red.log.</span>DEBUG
1.  number <span class="apidocSignatureSpan">node-red.log.</span>ERROR
1.  number <span class="apidocSignatureSpan">node-red.log.</span>FATAL
1.  number <span class="apidocSignatureSpan">node-red.log.</span>INFO
1.  number <span class="apidocSignatureSpan">node-red.log.</span>METRIC
1.  number <span class="apidocSignatureSpan">node-red.log.</span>TRACE
1.  number <span class="apidocSignatureSpan">node-red.log.</span>WARN

#### [module node-red.nodes](#apidoc.module.node-red.nodes)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>addCredentials (id, creds)](#apidoc.element.node-red.nodes.addCredentials)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>addFlow (flow)](#apidoc.element.node-red.nodes.addFlow)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>cleanModuleList ()](#apidoc.element.node-red.nodes.cleanModuleList)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>clearRegistry ()](#apidoc.element.node-red.nodes.clearRegistry)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>createNode (node, def)](#apidoc.element.node-red.nodes.createNode)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>deleteCredentials (id)](#apidoc.element.node-red.nodes.deleteCredentials)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>disableNode (id)](#apidoc.element.node-red.nodes.disableNode)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>eachNode (cb)](#apidoc.element.node-red.nodes.eachNode)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>enableNode (typeOrId)](#apidoc.element.node-red.nodes.enableNode)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>getCredentialDefinition (type)](#apidoc.element.node-red.nodes.getCredentialDefinition)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>getCredentials (id)](#apidoc.element.node-red.nodes.getCredentials)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>getFlow (id)](#apidoc.element.node-red.nodes.getFlow)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>getFlows ()](#apidoc.element.node-red.nodes.getFlows)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>getModuleInfo (module)](#apidoc.element.node-red.nodes.getModuleInfo)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>getNode (id)](#apidoc.element.node-red.nodes.getNode)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>getNodeConfig (id, lang)](#apidoc.element.node-red.nodes.getNodeConfig)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>getNodeConfigs (lang)](#apidoc.element.node-red.nodes.getNodeConfigs)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>getNodeInfo (typeOrId)](#apidoc.element.node-red.nodes.getNodeInfo)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>getNodeList (filter)](#apidoc.element.node-red.nodes.getNodeList)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>getType (type)](#apidoc.element.node-red.nodes.getType)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>init (runtime)](#apidoc.element.node-red.nodes.init)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>installModule (module)](#apidoc.element.node-red.nodes.installModule)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>load ()](#apidoc.element.node-red.nodes.load)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>loadFlows ()](#apidoc.element.node-red.nodes.loadFlows)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>paletteEditorEnabled ()](#apidoc.element.node-red.nodes.paletteEditorEnabled)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>registerType (nodeSet, type, constructor, opts)](#apidoc.element.node-red.nodes.registerType)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>removeFlow (id)](#apidoc.element.node-red.nodes.removeFlow)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>setFlows (_config, type, muteLog)](#apidoc.element.node-red.nodes.setFlows)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>startFlows (type, diff, muteLog)](#apidoc.element.node-red.nodes.startFlows)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>stopFlows (type, diff, muteLog)](#apidoc.element.node-red.nodes.stopFlows)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>uninstallModule (module)](#apidoc.element.node-red.nodes.uninstallModule)
1.  [function <span class="apidocSignatureSpan">node-red.nodes.</span>updateFlow (id, newFlow)](#apidoc.element.node-red.nodes.updateFlow)

#### [module node-red.settings](#apidoc.module.node-red.settings)
1.  boolean <span class="apidocSignatureSpan">node-red.settings.</span>disableEditor
1.  [function <span class="apidocSignatureSpan">node-red.settings.</span>available ()](#apidoc.element.node-red.settings.available)
1.  [function <span class="apidocSignatureSpan">node-red.settings.</span>delete (prop)](#apidoc.element.node-red.settings.delete)
1.  [function <span class="apidocSignatureSpan">node-red.settings.</span>get (prop)](#apidoc.element.node-red.settings.get)
1.  [function <span class="apidocSignatureSpan">node-red.settings.</span>init (settings)](#apidoc.element.node-red.settings.init)
1.  [function <span class="apidocSignatureSpan">node-red.settings.</span>load (_storage)](#apidoc.element.node-red.settings.load)
1.  [function <span class="apidocSignatureSpan">node-red.settings.</span>reset ()](#apidoc.element.node-red.settings.reset)
1.  [function <span class="apidocSignatureSpan">node-red.settings.</span>set (prop, value)](#apidoc.element.node-red.settings.set)
1.  number <span class="apidocSignatureSpan">node-red.settings.</span>debugMaxLength
1.  number <span class="apidocSignatureSpan">node-red.settings.</span>mqttReconnectTime
1.  number <span class="apidocSignatureSpan">node-red.settings.</span>serialReconnectTime
1.  object <span class="apidocSignatureSpan">node-red.settings.</span>functionGlobalContext
1.  object <span class="apidocSignatureSpan">node-red.settings.</span>logging
1.  string <span class="apidocSignatureSpan">node-red.settings.</span>coreNodesDir
1.  string <span class="apidocSignatureSpan">node-red.settings.</span>httpAdminRoot
1.  string <span class="apidocSignatureSpan">node-red.settings.</span>httpNodeRoot
1.  string <span class="apidocSignatureSpan">node-red.settings.</span>httpRoot
1.  string <span class="apidocSignatureSpan">node-red.settings.</span>settingsFile
1.  string <span class="apidocSignatureSpan">node-red.settings.</span>uiHost
1.  string <span class="apidocSignatureSpan">node-red.settings.</span>uiPort
1.  string <span class="apidocSignatureSpan">node-red.settings.</span>version

#### [module node-red.settings.functionGlobalContext](#apidoc.module.node-red.settings.functionGlobalContext)
1.  [function <span class="apidocSignatureSpan">node-red.settings.functionGlobalContext.</span>get (key)](#apidoc.element.node-red.settings.functionGlobalContext.get)
1.  [function <span class="apidocSignatureSpan">node-red.settings.functionGlobalContext.</span>set (key, value)](#apidoc.element.node-red.settings.functionGlobalContext.set)

#### [module node-red.util](#apidoc.module.node-red.util)
1.  [function <span class="apidocSignatureSpan">node-red.util.</span>cloneMessage (msg)](#apidoc.element.node-red.util.cloneMessage)
1.  [function <span class="apidocSignatureSpan">node-red.util.</span>compareObjects (obj1, obj2)](#apidoc.element.node-red.util.compareObjects)
1.  [function <span class="apidocSignatureSpan">node-red.util.</span>ensureBuffer (o)](#apidoc.element.node-red.util.ensureBuffer)
1.  [function <span class="apidocSignatureSpan">node-red.util.</span>ensureString (o)](#apidoc.element.node-red.util.ensureString)
1.  [function <span class="apidocSignatureSpan">node-red.util.</span>evaluateNodeProperty (value, type, node, msg)](#apidoc.element.node-red.util.evaluateNodeProperty)
1.  [function <span class="apidocSignatureSpan">node-red.util.</span>generateId ()](#apidoc.element.node-red.util.generateId)
1.  [function <span class="apidocSignatureSpan">node-red.util.</span>getMessageProperty (msg, expr)](#apidoc.element.node-red.util.getMessageProperty)
1.  [function <span class="apidocSignatureSpan">node-red.util.</span>normalisePropertyExpression (str)](#apidoc.element.node-red.util.normalisePropertyExpression)
1.  [function <span class="apidocSignatureSpan">node-red.util.</span>setMessageProperty (msg, prop, value, createMissing)](#apidoc.element.node-red.util.setMessageProperty)



# <a name="apidoc.module.node-red"></a>[module node-red](#apidoc.module.node-red)

#### <a name="apidoc.element.node-red.httpAdmin"></a>[function <span class="apidocSignatureSpan">node-red.</span>httpAdmin (req, res, next)](#apidoc.element.node-red.httpAdmin)
- description and source-code
```javascript
httpAdmin = function (req, res, next) {
  app.handle(req, res, next);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent"></a>[function <span class="apidocSignatureSpan">node-red.</span>httpAdmin.parent (req, res, next)](#apidoc.element.node-red.httpAdmin.parent)
- description and source-code
```javascript
httpAdmin.parent = function (req, res, next) {
  app.handle(req, res, next);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode"></a>[function <span class="apidocSignatureSpan">node-red.</span>httpNode (req, res, next)](#apidoc.element.node-red.httpNode)
- description and source-code
```javascript
httpNode = function (req, res, next) {
  app.handle(req, res, next);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.init"></a>[function <span class="apidocSignatureSpan">node-red.</span>init (httpServer, userSettings)](#apidoc.element.node-red.init)
- description and source-code
```javascript
init = function (httpServer, userSettings) {
    if (!userSettings) {
        userSettings = httpServer;
        httpServer = null;
    }

    if (!userSettings.SKIP_BUILD_CHECK) {
        checkVersion(userSettings);
        checkBuild();
    }

    if (!userSettings.coreNodesDir) {
        userSettings.coreNodesDir = path.resolve(path.join(__dirname,"..","nodes"));
    }

    if (userSettings.httpAdminRoot !== false) {
        runtime.init(userSettings,api);
        api.init(httpServer,runtime);
        apiEnabled = true;
    } else {
        runtime.init(userSettings);
        apiEnabled = false;
    }
    adminApp = runtime.adminApi.adminApp;
    nodeApp = runtime.nodeApp;
    server = runtime.adminApi.server;
    return;
}
```
- example usage
```shell
...
settings.flowFile = flowFile;
}
if (parsedArgs.userDir) {
settings.userDir = parsedArgs.userDir;
}

try {
RED.init(server,settings);
} catch(err) {
if (err.code == "unsupported_version") {
    console.log("Unsupported version of node.js:",process.version);
    console.log("Node-RED requires node.js v4 or later");
} else if  (err.code == "not_built") {
    console.log("Node-RED has not been built. See README.md for details");
} else {
...
```

#### <a name="apidoc.element.node-red.start"></a>[function <span class="apidocSignatureSpan">node-red.</span>start ()](#apidoc.element.node-red.start)
- description and source-code
```javascript
start = function () {
    return runtime.start().then(function() {
        if (apiEnabled) {
            return api.start();
        }
    });
}
```
- example usage
```shell
...
    listenPath += settings.httpAdminRoot;
} else if (settings.httpStatic) {
    listenPath += "/";
}
return listenPath;
}

RED.start().then(function() {
if (settings.httpAdminRoot !== false || settings.httpNodeRoot !== false || settings.httpStatic) {
    server.on('error', function(err) {
        if (err.errno === "EADDRINUSE") {
            RED.log.error(RED.log._("server.unable-to-listen", {listenpath:getListenPath()}));
            RED.log.error(RED.log._("server.port-in-use"));
        } else {
            RED.log.error(RED.log._("server.uncaught-exception"));
...
```

#### <a name="apidoc.element.node-red.stop"></a>[function <span class="apidocSignatureSpan">node-red.</span>stop ()](#apidoc.element.node-red.stop)
- description and source-code
```javascript
stop = function () {
    return runtime.stop().then(function() {
        if (apiEnabled) {
            return api.stop();
        }
    })
}
```
- example usage
```shell
...
    } else {
        util.log(err);
    }
    process.exit(1);
});

process.on('SIGINT', function () {
    RED.stop();
    // TODO: need to allow nodes to close asynchronously before terminating the
    // process - ie, promises
    process.exit();
});
...
```

#### <a name="apidoc.element.node-red.version"></a>[function <span class="apidocSignatureSpan">node-red.</span>version ()](#apidoc.element.node-red.version)
- description and source-code
```javascript
function getVersion() {
    if (!version) {
        version = require(path.join(__dirname,"..","..","package.json")).version;
<span class="apidocCodeCommentSpan">        /* istanbul ignore else */
</span>        try {
            fs.statSync(path.join(__dirname,"..","..",".git"));
            version += "-git";
        } catch(err) {
            // No git directory
        }
    }
    return version;
}
```
- example usage
```shell
...
nopt.invalidHandler = function(k,v,t) {
// TODO: console.log(k,v,t);
}

var parsedArgs = nopt(knownOpts,shortHands,process.argv,2)

if (parsedArgs.help) {
console.log("Node-RED v"+RED.version());
console.log("Usage: node-red [-v] [-?] [--settings settings.js] [--userDir DIR]");
console.log("                [--port PORT] [--title TITLE] [flows.json]");
console.log("");
console.log("Options:");
console.log("  -p, --port     PORT  port to listen on");
console.log("  -s, --settings FILE  use specified settings file");
console.log("      --title    TITLE process window title");
...
```



# <a name="apidoc.module.node-red.auth"></a>[module node-red.auth](#apidoc.module.node-red.auth)

#### <a name="apidoc.element.node-red.auth.needsPermission"></a>[function <span class="apidocSignatureSpan">node-red.auth.</span>needsPermission (permission)](#apidoc.element.node-red.auth.needsPermission)
- description and source-code
```javascript
function needsPermission(permission) {
    return function(req,res,next) {
        if (settings && settings.adminAuth) {
            return passport.authenticate(['bearer','anon'],{ session: false })(req,res,function() {
                if (!req.user) {
                    return next();
                }
                if (permissions.hasPermission(req.authInfo.scope,permission)) {
                    return next();
                }
                log.audit({event: "permission.fail", permissions: permission},req);
                return res.status(401).end();
            });
        } else {
            next();
        }
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-red.comms"></a>[module node-red.comms](#apidoc.module.node-red.comms)

#### <a name="apidoc.element.node-red.comms.publish"></a>[function <span class="apidocSignatureSpan">node-red.comms.</span>publish (topic, data, retain)](#apidoc.element.node-red.comms.publish)
- description and source-code
```javascript
function publish(topic, data, retain) {
    if (server) {
        if (retain) {
            retained[topic] = data;
        } else {
            delete retained[topic];
        }
        lastSentTime = Date.now();
        activeConnections.forEach(function(conn) {
            publishTo(conn,topic,data);
        });
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-red.httpAdmin"></a>[module node-red.httpAdmin](#apidoc.module.node-red.httpAdmin)

#### <a name="apidoc.element.node-red.httpAdmin.httpAdmin"></a>[function <span class="apidocSignatureSpan">node-red.</span>httpAdmin (req, res, next)](#apidoc.element.node-red.httpAdmin.httpAdmin)
- description and source-code
```javascript
httpAdmin = function (req, res, next) {
  app.handle(req, res, next);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin._router"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>_router (req, res, next)](#apidoc.element.node-red.httpAdmin._router)
- description and source-code
```javascript
function router(req, res, next) {
  router.handle(req, res, next);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.acl"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>acl (path)](#apidoc.element.node-red.httpAdmin.acl)
- description and source-code
```javascript
acl = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.addListener"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>addListener (type, listener)](#apidoc.element.node-red.httpAdmin.addListener)
- description and source-code
```javascript
function addListener(type, listener) {
  return _addListener(this, type, listener, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.all"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>all (path)](#apidoc.element.node-red.httpAdmin.all)
- description and source-code
```javascript
function all(path) {
  this.lazyrouter();

  var route = this._router.route(path);
  var args = slice.call(arguments, 1);

  for (var i = 0; i < methods.length; i++) {
    route[methods[i]].apply(route, args);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.bind"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>bind (path)](#apidoc.element.node-red.httpAdmin.bind)
- description and source-code
```javascript
bind = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.checkout"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>checkout (path)](#apidoc.element.node-red.httpAdmin.checkout)
- description and source-code
```javascript
checkout = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.connect"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>connect (path)](#apidoc.element.node-red.httpAdmin.connect)
- description and source-code
```javascript
connect = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.copy"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>copy (path)](#apidoc.element.node-red.httpAdmin.copy)
- description and source-code
```javascript
copy = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.defaultConfiguration"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>defaultConfiguration ()](#apidoc.element.node-red.httpAdmin.defaultConfiguration)
- description and source-code
```javascript
function defaultConfiguration() {
  var env = process.env.NODE_ENV || 'development';

  // default settings
  this.enable('x-powered-by');
  this.set('etag', 'weak');
  this.set('env', env);
  this.set('query parser', 'extended');
  this.set('subdomain offset', 2);
  this.set('trust proxy', false);

  // trust proxy inherit back-compat
  Object.defineProperty(this.settings, trustProxyDefaultSymbol, {
    configurable: true,
    value: true
  });

  debug('booting in %s mode', env);

  this.on('mount', function onmount(parent) {
    // inherit trust proxy
    if (this.settings[trustProxyDefaultSymbol] === true
      && typeof parent.settings['trust proxy fn'] === 'function') {
      delete this.settings['trust proxy'];
      delete this.settings['trust proxy fn'];
    }

    // inherit protos
    this.request.__proto__ = parent.request;
    this.response.__proto__ = parent.response;
    this.engines.__proto__ = parent.engines;
    this.settings.__proto__ = parent.settings;
  });

  // setup locals
  this.locals = Object.create(null);

  // top-most app is mounted at /
  this.mountpath = '/';

  // default locals
  this.locals.settings = this.settings;

  // default configuration
  this.set('view', View);
  this.set('views', resolve('views'));
  this.set('jsonp callback name', 'callback');

  if (env === 'production') {
    this.enable('view cache');
  }

  Object.defineProperty(this, 'router', {
    get: function() {
      throw new Error('\'app.router\' is deprecated!\nPlease see the 3.x to 4.x migration guide for details on how to update your
 app.');
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.del"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>del (arg0)](#apidoc.element.node-red.httpAdmin.del)
- description and source-code
```javascript
del = function (arg0) {
"use strict"
log.call(deprecate, message, site)
return fn.apply(this, arguments)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.delete"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>delete (path)](#apidoc.element.node-red.httpAdmin.delete)
- description and source-code
```javascript
delete = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.disable"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>disable (setting)](#apidoc.element.node-red.httpAdmin.disable)
- description and source-code
```javascript
function disable(setting) {
  return this.set(setting, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.disabled"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>disabled (setting)](#apidoc.element.node-red.httpAdmin.disabled)
- description and source-code
```javascript
function disabled(setting) {
  return !this.set(setting);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.emit"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>emit (type)](#apidoc.element.node-red.httpAdmin.emit)
- description and source-code
```javascript
function emit(type) {
  var er, handler, len, args, i, events, domain;
  var needDomainExit = false;
  var doError = (type === 'error');

  events = this._events;
  if (events)
    doError = (doError && events.error == null);
  else if (!doError)
    return false;

  domain = this.domain;

  // If there is no 'error' event listener then throw.
  if (doError) {
    er = arguments[1];
    if (domain) {
      if (!er)
        er = new Error('Uncaught, unspecified "error" event');
      er.domainEmitter = this;
      er.domain = domain;
      er.domainThrown = false;
      domain.emit('error', er);
    } else if (er instanceof Error) {
      throw er; // Unhandled 'error' event
    } else {
      // At least give some kind of context to the user
      var err = new Error('Uncaught, unspecified "error" event. (' + er + ')');
      err.context = er;
      throw err;
    }
    return false;
  }

  handler = events[type];

  if (!handler)
    return false;

  if (domain && this !== process) {
    domain.enter();
    needDomainExit = true;
  }

  var isFn = typeof handler === 'function';
  len = arguments.length;
  switch (len) {
    // fast cases
    case 1:
      emitNone(handler, isFn, this);
      break;
    case 2:
      emitOne(handler, isFn, this, arguments[1]);
      break;
    case 3:
      emitTwo(handler, isFn, this, arguments[1], arguments[2]);
      break;
    case 4:
      emitThree(handler, isFn, this, arguments[1], arguments[2], arguments[3]);
      break;
    // slower
    default:
      args = new Array(len - 1);
      for (i = 1; i < len; i++)
        args[i - 1] = arguments[i];
      emitMany(handler, isFn, this, args);
  }

  if (needDomainExit)
    domain.exit();

  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.enable"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>enable (setting)](#apidoc.element.node-red.httpAdmin.enable)
- description and source-code
```javascript
function enable(setting) {
  return this.set(setting, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.enabled"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>enabled (setting)](#apidoc.element.node-red.httpAdmin.enabled)
- description and source-code
```javascript
function enabled(setting) {
  return Boolean(this.set(setting));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.engine"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>engine (ext, fn)](#apidoc.element.node-red.httpAdmin.engine)
- description and source-code
```javascript
function engine(ext, fn) {
  if (typeof fn !== 'function') {
    throw new Error('callback function required');
  }

  // get file extension
  var extension = ext[0] !== '.'
    ? '.' + ext
    : ext;

  // store engine
  this.engines[extension] = fn;

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.eventNames"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>eventNames ()](#apidoc.element.node-red.httpAdmin.eventNames)
- description and source-code
```javascript
function eventNames() {
  return this._eventsCount > 0 ? Reflect.ownKeys(this._events) : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.get"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>get (path)](#apidoc.element.node-red.httpAdmin.get)
- description and source-code
```javascript
get = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.getMaxListeners"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>getMaxListeners ()](#apidoc.element.node-red.httpAdmin.getMaxListeners)
- description and source-code
```javascript
function getMaxListeners() {
  return $getMaxListeners(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.handle"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>handle (req, res, callback)](#apidoc.element.node-red.httpAdmin.handle)
- description and source-code
```javascript
function handle(req, res, callback) {
  var router = this._router;

  // final handler
  var done = callback || finalhandler(req, res, {
    env: this.get('env'),
    onerror: logerror.bind(this)
  });

  // no routes
  if (!router) {
    debug('no routes defined on app');
    done();
    return;
  }

  router.handle(req, res, done);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.head"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>head (path)](#apidoc.element.node-red.httpAdmin.head)
- description and source-code
```javascript
head = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.init"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>init ()](#apidoc.element.node-red.httpAdmin.init)
- description and source-code
```javascript
function init() {
  this.cache = {};
  this.engines = {};
  this.settings = {};

  this.defaultConfiguration();
}
```
- example usage
```shell
...
settings.flowFile = flowFile;
}
if (parsedArgs.userDir) {
settings.userDir = parsedArgs.userDir;
}

try {
RED.init(server,settings);
} catch(err) {
if (err.code == "unsupported_version") {
    console.log("Unsupported version of node.js:",process.version);
    console.log("Node-RED requires node.js v4 or later");
} else if  (err.code == "not_built") {
    console.log("Node-RED has not been built. See README.md for details");
} else {
...
```

#### <a name="apidoc.element.node-red.httpAdmin.lazyrouter"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>lazyrouter ()](#apidoc.element.node-red.httpAdmin.lazyrouter)
- description and source-code
```javascript
function lazyrouter() {
  if (!this._router) {
    this._router = new Router({
      caseSensitive: this.enabled('case sensitive routing'),
      strict: this.enabled('strict routing')
    });

    this._router.use(query(this.get('query parser fn')));
    this._router.use(middleware.init(this));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.link"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>link (path)](#apidoc.element.node-red.httpAdmin.link)
- description and source-code
```javascript
link = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.listen"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>listen ()](#apidoc.element.node-red.httpAdmin.listen)
- description and source-code
```javascript
function listen() {
  var server = http.createServer(this);
  return server.listen.apply(server, arguments);
}
```
- example usage
```shell
...
                RED.log.error(err.stack);
            } else {
                RED.log.error(err);
            }
        }
        process.exit(1);
    });
    server.listen(settings.uiPort,settings.uiHost,function() {
        if (settings.httpAdminRoot === false) {
            RED.log.info(RED.log._("server.admin-ui-disabled"));
        }
        process.title = parsedArgs.title || 'node-red';
        RED.log.info(RED.log._("server.now-running", {listenpath:getListenPath()}));
    });
} else {
...
```

#### <a name="apidoc.element.node-red.httpAdmin.listenerCount"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>listenerCount (type)](#apidoc.element.node-red.httpAdmin.listenerCount)
- description and source-code
```javascript
function listenerCount(type) {
  const events = this._events;

  if (events) {
    const evlistener = events[type];

    if (typeof evlistener === 'function') {
      return 1;
    } else if (evlistener) {
      return evlistener.length;
    }
  }

  return 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.listeners"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>listeners (type)](#apidoc.element.node-red.httpAdmin.listeners)
- description and source-code
```javascript
function listeners(type) {
  var evlistener;
  var ret;
  var events = this._events;

  if (!events)
    ret = [];
  else {
    evlistener = events[type];
    if (!evlistener)
      ret = [];
    else if (typeof evlistener === 'function')
      ret = [evlistener];
    else
      ret = arrayClone(evlistener, evlistener.length);
  }

  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.lock"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>lock (path)](#apidoc.element.node-red.httpAdmin.lock)
- description and source-code
```javascript
lock = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.m-search"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>m-search (path)](#apidoc.element.node-red.httpAdmin.m-search)
- description and source-code
```javascript
m-search = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.merge"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>merge (path)](#apidoc.element.node-red.httpAdmin.merge)
- description and source-code
```javascript
merge = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.mkactivity"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>mkactivity (path)](#apidoc.element.node-red.httpAdmin.mkactivity)
- description and source-code
```javascript
mkactivity = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.mkcalendar"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>mkcalendar (path)](#apidoc.element.node-red.httpAdmin.mkcalendar)
- description and source-code
```javascript
mkcalendar = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.mkcol"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>mkcol (path)](#apidoc.element.node-red.httpAdmin.mkcol)
- description and source-code
```javascript
mkcol = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.move"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>move (path)](#apidoc.element.node-red.httpAdmin.move)
- description and source-code
```javascript
move = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.notify"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>notify (path)](#apidoc.element.node-red.httpAdmin.notify)
- description and source-code
```javascript
notify = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.on"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>on (type, listener)](#apidoc.element.node-red.httpAdmin.on)
- description and source-code
```javascript
function addListener(type, listener) {
  return _addListener(this, type, listener, false);
}
```
- example usage
```shell
...
    listenPath += "/";
}
return listenPath;
}

RED.start().then(function() {
if (settings.httpAdminRoot !== false || settings.httpNodeRoot !== false || settings.httpStatic) {
    server.on('error', function(err) {
        if (err.errno === "EADDRINUSE") {
            RED.log.error(RED.log._("server.unable-to-listen", {listenpath:getListenPath()}));
            RED.log.error(RED.log._("server.port-in-use"));
        } else {
            RED.log.error(RED.log._("server.uncaught-exception"));
            if (err.stack) {
                RED.log.error(err.stack);
...
```

#### <a name="apidoc.element.node-red.httpAdmin.once"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>once (type, listener)](#apidoc.element.node-red.httpAdmin.once)
- description and source-code
```javascript
function once(type, listener) {
  if (typeof listener !== 'function')
    throw new TypeError('"listener" argument must be a function');
  this.on(type, _onceWrap(this, type, listener));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.options"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>options (path)](#apidoc.element.node-red.httpAdmin.options)
- description and source-code
```javascript
options = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.param"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>param (name, fn)](#apidoc.element.node-red.httpAdmin.param)
- description and source-code
```javascript
function param(name, fn) {
  this.lazyrouter();

  if (Array.isArray(name)) {
    for (var i = 0; i < name.length; i++) {
      this.param(name[i], fn);
    }

    return this;
  }

  this._router.param(name, fn);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>parent (req, res, next)](#apidoc.element.node-red.httpAdmin.parent)
- description and source-code
```javascript
parent = function (req, res, next) {
  app.handle(req, res, next);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.patch"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>patch (path)](#apidoc.element.node-red.httpAdmin.patch)
- description and source-code
```javascript
patch = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.path"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>path ()](#apidoc.element.node-red.httpAdmin.path)
- description and source-code
```javascript
function path() {
  return this.parent
    ? this.parent.path() + this.mountpath
    : '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.post"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>post (path)](#apidoc.element.node-red.httpAdmin.post)
- description and source-code
```javascript
post = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.prependListener"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>prependListener (type, listener)](#apidoc.element.node-red.httpAdmin.prependListener)
- description and source-code
```javascript
function prependListener(type, listener) {
  return _addListener(this, type, listener, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.prependOnceListener"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>prependOnceListener (type, listener)](#apidoc.element.node-red.httpAdmin.prependOnceListener)
- description and source-code
```javascript
function prependOnceListener(type, listener) {
  if (typeof listener !== 'function')
    throw new TypeError('"listener" argument must be a function');
  this.prependListener(type, _onceWrap(this, type, listener));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.propfind"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>propfind (path)](#apidoc.element.node-red.httpAdmin.propfind)
- description and source-code
```javascript
propfind = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.proppatch"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>proppatch (path)](#apidoc.element.node-red.httpAdmin.proppatch)
- description and source-code
```javascript
proppatch = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.purge"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>purge (path)](#apidoc.element.node-red.httpAdmin.purge)
- description and source-code
```javascript
purge = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.put"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>put (path)](#apidoc.element.node-red.httpAdmin.put)
- description and source-code
```javascript
put = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.rebind"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>rebind (path)](#apidoc.element.node-red.httpAdmin.rebind)
- description and source-code
```javascript
rebind = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.removeAllListeners"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>removeAllListeners (type)](#apidoc.element.node-red.httpAdmin.removeAllListeners)
- description and source-code
```javascript
function removeAllListeners(type) {
  var listeners, events;

  events = this._events;
  if (!events)
    return this;

  // not listening for removeListener, no need to emit
  if (!events.removeListener) {
    if (arguments.length === 0) {
      this._events = new EventHandlers();
      this._eventsCount = 0;
    } else if (events[type]) {
      if (--this._eventsCount === 0)
        this._events = new EventHandlers();
      else
        delete events[type];
    }
    return this;
  }

  // emit removeListener for all listeners on all events
  if (arguments.length === 0) {
    var keys = Object.keys(events);
    for (var i = 0, key; i < keys.length; ++i) {
      key = keys[i];
      if (key === 'removeListener') continue;
      this.removeAllListeners(key);
    }
    this.removeAllListeners('removeListener');
    this._events = new EventHandlers();
    this._eventsCount = 0;
    return this;
  }

  listeners = events[type];

  if (typeof listeners === 'function') {
    this.removeListener(type, listeners);
  } else if (listeners) {
    // LIFO order
    do {
      this.removeListener(type, listeners[listeners.length - 1]);
    } while (listeners[0]);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.removeListener"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>removeListener (type, listener)](#apidoc.element.node-red.httpAdmin.removeListener)
- description and source-code
```javascript
function removeListener(type, listener) {
  var list, events, position, i, originalListener;

  if (typeof listener !== 'function')
    throw new TypeError('"listener" argument must be a function');

  events = this._events;
  if (!events)
    return this;

  list = events[type];
  if (!list)
    return this;

  if (list === listener || list.listener === listener) {
    if (--this._eventsCount === 0)
      this._events = new EventHandlers();
    else {
      delete events[type];
      if (events.removeListener)
        this.emit('removeListener', type, list.listener || listener);
    }
  } else if (typeof list !== 'function') {
    position = -1;

    for (i = list.length; i-- > 0;) {
      if (list[i] === listener || list[i].listener === listener) {
        originalListener = list[i].listener;
        position = i;
        break;
      }
    }

    if (position < 0)
      return this;

    if (list.length === 1) {
      list[0] = undefined;
      if (--this._eventsCount === 0) {
        this._events = new EventHandlers();
        return this;
      } else {
        delete events[type];
      }
    } else {
      spliceOne(list, position);
    }

    if (events.removeListener)
      this.emit('removeListener', type, originalListener || listener);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.render"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>render (name, options, callback)](#apidoc.element.node-red.httpAdmin.render)
- description and source-code
```javascript
function render(name, options, callback) {
  var cache = this.cache;
  var done = callback;
  var engines = this.engines;
  var opts = options;
  var renderOptions = {};
  var view;

  // support callback function as second arg
  if (typeof options === 'function') {
    done = options;
    opts = {};
  }

  // merge app.locals
  merge(renderOptions, this.locals);

  // merge options._locals
  if (opts._locals) {
    merge(renderOptions, opts._locals);
  }

  // merge options
  merge(renderOptions, opts);

  // set .cache unless explicitly provided
  if (renderOptions.cache == null) {
    renderOptions.cache = this.enabled('view cache');
  }

  // primed cache
  if (renderOptions.cache) {
    view = cache[name];
  }

  // view
  if (!view) {
    var View = this.get('view');

    view = new View(name, {
      defaultEngine: this.get('view engine'),
      root: this.get('views'),
      engines: engines
    });

    if (!view.path) {
      var dirs = Array.isArray(view.root) && view.root.length > 1
        ? 'directories "' + view.root.slice(0, -1).join('", "') + '" or "' + view.root[view.root.length - 1] + '"'
        : 'directory "' + view.root + '"'
      var err = new Error('Failed to lookup view "' + name + '" in views ' + dirs);
      err.view = view;
      return done(err);
    }

    // prime the cache
    if (renderOptions.cache) {
      cache[name] = view;
    }
  }

  // render
  tryRender(view, renderOptions, done);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.report"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>report (path)](#apidoc.element.node-red.httpAdmin.report)
- description and source-code
```javascript
report = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.route"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>route (path)](#apidoc.element.node-red.httpAdmin.route)
- description and source-code
```javascript
function route(path) {
  this.lazyrouter();
  return this._router.route(path);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.search"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>search (path)](#apidoc.element.node-red.httpAdmin.search)
- description and source-code
```javascript
search = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.set"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>set (setting, val)](#apidoc.element.node-red.httpAdmin.set)
- description and source-code
```javascript
function set(setting, val) {
  if (arguments.length === 1) {
    // app.get(setting)
    return this.settings[setting];
  }

  debug('set "%s" to %o', setting, val);

  // set value
  this.settings[setting] = val;

  // trigger matched settings
  switch (setting) {
    case 'etag':
      this.set('etag fn', compileETag(val));
      break;
    case 'query parser':
      this.set('query parser fn', compileQueryParser(val));
      break;
    case 'trust proxy':
      this.set('trust proxy fn', compileTrust(val));

      // trust proxy inherit back-compat
      Object.defineProperty(this.settings, trustProxyDefaultSymbol, {
        configurable: true,
        value: false
      });

      break;
  }

  return this;
}
```
- example usage
```shell
...

    return function(req,res,next) {
        if (req.method === 'OPTIONS') {
            return next();
        }
        var requestUser = basicAuth(req);
        if (!requestUser || requestUser.name !== user || !checkPassword(requestUser.pass)) {
            res.set('WWW-Authenticate', 'Basic realm=Authorization Required');
            return res.sendStatus(401);
        }
        next();
    }
}

if (settings.httpAdminRoot !== false && settings.httpAdminAuth) {
...
```

#### <a name="apidoc.element.node-red.httpAdmin.setMaxListeners"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>setMaxListeners (n)](#apidoc.element.node-red.httpAdmin.setMaxListeners)
- description and source-code
```javascript
function setMaxListeners(n) {
  if (typeof n !== 'number' || n < 0 || isNaN(n))
    throw new TypeError('"n" argument must be a positive number');
  this._maxListeners = n;
  return this;
}
```
- example usage
```shell
...
}

if (settings.https) {
server = https.createServer(settings.https,function(req,res) {app(req,res);});
} else {
server = http.createServer(function(req,res) {app(req,res);});
}
server.setMaxListeners(0);

function formatRoot(root) {
if (root[0] != "/") {
    root = "/" + root;
}
if (root.slice(-1) != "/") {
    root = root + "/";
...
```

#### <a name="apidoc.element.node-red.httpAdmin.subscribe"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>subscribe (path)](#apidoc.element.node-red.httpAdmin.subscribe)
- description and source-code
```javascript
subscribe = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.trace"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>trace (path)](#apidoc.element.node-red.httpAdmin.trace)
- description and source-code
```javascript
trace = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.unbind"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>unbind (path)](#apidoc.element.node-red.httpAdmin.unbind)
- description and source-code
```javascript
unbind = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.unlink"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>unlink (path)](#apidoc.element.node-red.httpAdmin.unlink)
- description and source-code
```javascript
unlink = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.unlock"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>unlock (path)](#apidoc.element.node-red.httpAdmin.unlock)
- description and source-code
```javascript
unlock = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.unsubscribe"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>unsubscribe (path)](#apidoc.element.node-red.httpAdmin.unsubscribe)
- description and source-code
```javascript
unsubscribe = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.use"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>use (fn)](#apidoc.element.node-red.httpAdmin.use)
- description and source-code
```javascript
function use(fn) {
  var offset = 0;
  var path = '/';

  // default path to '/'
  // disambiguate app.use([fn])
  if (typeof fn !== 'function') {
    var arg = fn;

    while (Array.isArray(arg) && arg.length !== 0) {
      arg = arg[0];
    }

    // first arg is the path
    if (typeof arg !== 'function') {
      offset = 1;
      path = fn;
    }
  }

  var fns = flatten(slice.call(arguments, offset));

  if (fns.length === 0) {
    throw new TypeError('app.use() requires middleware functions');
  }

  // setup router
  this.lazyrouter();
  var router = this._router;

  fns.forEach(function (fn) {
    // non-express app
    if (!fn || !fn.handle || !fn.set) {
      return router.use(path, fn);
    }

    debug('.use app under %s', path);
    fn.mountpath = path;
    fn.parent = this;

    // restore .app property on req and res
    router.use(path, function mounted_app(req, res, next) {
      var orig = req.app;
      fn.handle(req, res, function (err) {
        req.__proto__ = orig.request;
        res.__proto__ = orig.response;
        next(err);
      });
    });

    // mounted an app
    fn.emit('mount', this);
  }, this);

  return this;
}
```
- example usage
```shell
...
    }
    next();
}
}

if (settings.httpAdminRoot !== false && settings.httpAdminAuth) {
RED.log.warn(RED.log._("server.httpadminauth-deprecated"));
app.use(settings.httpAdminRoot, basicAuthMiddleware(settings.httpAdminAuth.user,settings.httpAdminAuth.pass));
}

if (settings.httpAdminRoot !== false) {
app.use(settings.httpAdminRoot,RED.httpAdmin);
}
if (settings.httpNodeRoot !== false && settings.httpNodeAuth) {
app.use(settings.httpNodeRoot,basicAuthMiddleware(settings.httpNodeAuth.user,settings.httpNodeAuth.pass));
...
```



# <a name="apidoc.module.node-red.httpAdmin._events"></a>[module node-red.httpAdmin._events](#apidoc.module.node-red.httpAdmin._events)

#### <a name="apidoc.element.node-red.httpAdmin._events.mount"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin._events.</span>mount (parent)](#apidoc.element.node-red.httpAdmin._events.mount)
- description and source-code
```javascript
function onmount(parent) {
  // inherit trust proxy
  if (this.settings[trustProxyDefaultSymbol] === true
    && typeof parent.settings['trust proxy fn'] === 'function') {
    delete this.settings['trust proxy'];
    delete this.settings['trust proxy fn'];
  }

  // inherit protos
  this.request.__proto__ = parent.request;
  this.response.__proto__ = parent.response;
  this.engines.__proto__ = parent.engines;
  this.settings.__proto__ = parent.settings;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-red.httpAdmin.parent"></a>[module node-red.httpAdmin.parent](#apidoc.module.node-red.httpAdmin.parent)

#### <a name="apidoc.element.node-red.httpAdmin.parent.parent"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.</span>parent (req, res, next)](#apidoc.element.node-red.httpAdmin.parent.parent)
- description and source-code
```javascript
parent = function (req, res, next) {
  app.handle(req, res, next);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent._router"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>_router (req, res, next)](#apidoc.element.node-red.httpAdmin.parent._router)
- description and source-code
```javascript
function router(req, res, next) {
  router.handle(req, res, next);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.acl"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>acl (path)](#apidoc.element.node-red.httpAdmin.parent.acl)
- description and source-code
```javascript
acl = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.addListener"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>addListener (type, listener)](#apidoc.element.node-red.httpAdmin.parent.addListener)
- description and source-code
```javascript
function addListener(type, listener) {
  return _addListener(this, type, listener, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.all"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>all (path)](#apidoc.element.node-red.httpAdmin.parent.all)
- description and source-code
```javascript
function all(path) {
  this.lazyrouter();

  var route = this._router.route(path);
  var args = slice.call(arguments, 1);

  for (var i = 0; i < methods.length; i++) {
    route[methods[i]].apply(route, args);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.bind"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>bind (path)](#apidoc.element.node-red.httpAdmin.parent.bind)
- description and source-code
```javascript
bind = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.checkout"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>checkout (path)](#apidoc.element.node-red.httpAdmin.parent.checkout)
- description and source-code
```javascript
checkout = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.connect"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>connect (path)](#apidoc.element.node-red.httpAdmin.parent.connect)
- description and source-code
```javascript
connect = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.copy"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>copy (path)](#apidoc.element.node-red.httpAdmin.parent.copy)
- description and source-code
```javascript
copy = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.defaultConfiguration"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>defaultConfiguration ()](#apidoc.element.node-red.httpAdmin.parent.defaultConfiguration)
- description and source-code
```javascript
function defaultConfiguration() {
  var env = process.env.NODE_ENV || 'development';

  // default settings
  this.enable('x-powered-by');
  this.set('etag', 'weak');
  this.set('env', env);
  this.set('query parser', 'extended');
  this.set('subdomain offset', 2);
  this.set('trust proxy', false);

  // trust proxy inherit back-compat
  Object.defineProperty(this.settings, trustProxyDefaultSymbol, {
    configurable: true,
    value: true
  });

  debug('booting in %s mode', env);

  this.on('mount', function onmount(parent) {
    // inherit trust proxy
    if (this.settings[trustProxyDefaultSymbol] === true
      && typeof parent.settings['trust proxy fn'] === 'function') {
      delete this.settings['trust proxy'];
      delete this.settings['trust proxy fn'];
    }

    // inherit protos
    this.request.__proto__ = parent.request;
    this.response.__proto__ = parent.response;
    this.engines.__proto__ = parent.engines;
    this.settings.__proto__ = parent.settings;
  });

  // setup locals
  this.locals = Object.create(null);

  // top-most app is mounted at /
  this.mountpath = '/';

  // default locals
  this.locals.settings = this.settings;

  // default configuration
  this.set('view', View);
  this.set('views', resolve('views'));
  this.set('jsonp callback name', 'callback');

  if (env === 'production') {
    this.enable('view cache');
  }

  Object.defineProperty(this, 'router', {
    get: function() {
      throw new Error('\'app.router\' is deprecated!\nPlease see the 3.x to 4.x migration guide for details on how to update your
 app.');
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.del"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>del (arg0)](#apidoc.element.node-red.httpAdmin.parent.del)
- description and source-code
```javascript
del = function (arg0) {
"use strict"
log.call(deprecate, message, site)
return fn.apply(this, arguments)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.delete"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>delete (path)](#apidoc.element.node-red.httpAdmin.parent.delete)
- description and source-code
```javascript
delete = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.disable"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>disable (setting)](#apidoc.element.node-red.httpAdmin.parent.disable)
- description and source-code
```javascript
function disable(setting) {
  return this.set(setting, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.disabled"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>disabled (setting)](#apidoc.element.node-red.httpAdmin.parent.disabled)
- description and source-code
```javascript
function disabled(setting) {
  return !this.set(setting);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.emit"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>emit (type)](#apidoc.element.node-red.httpAdmin.parent.emit)
- description and source-code
```javascript
function emit(type) {
  var er, handler, len, args, i, events, domain;
  var needDomainExit = false;
  var doError = (type === 'error');

  events = this._events;
  if (events)
    doError = (doError && events.error == null);
  else if (!doError)
    return false;

  domain = this.domain;

  // If there is no 'error' event listener then throw.
  if (doError) {
    er = arguments[1];
    if (domain) {
      if (!er)
        er = new Error('Uncaught, unspecified "error" event');
      er.domainEmitter = this;
      er.domain = domain;
      er.domainThrown = false;
      domain.emit('error', er);
    } else if (er instanceof Error) {
      throw er; // Unhandled 'error' event
    } else {
      // At least give some kind of context to the user
      var err = new Error('Uncaught, unspecified "error" event. (' + er + ')');
      err.context = er;
      throw err;
    }
    return false;
  }

  handler = events[type];

  if (!handler)
    return false;

  if (domain && this !== process) {
    domain.enter();
    needDomainExit = true;
  }

  var isFn = typeof handler === 'function';
  len = arguments.length;
  switch (len) {
    // fast cases
    case 1:
      emitNone(handler, isFn, this);
      break;
    case 2:
      emitOne(handler, isFn, this, arguments[1]);
      break;
    case 3:
      emitTwo(handler, isFn, this, arguments[1], arguments[2]);
      break;
    case 4:
      emitThree(handler, isFn, this, arguments[1], arguments[2], arguments[3]);
      break;
    // slower
    default:
      args = new Array(len - 1);
      for (i = 1; i < len; i++)
        args[i - 1] = arguments[i];
      emitMany(handler, isFn, this, args);
  }

  if (needDomainExit)
    domain.exit();

  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.enable"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>enable (setting)](#apidoc.element.node-red.httpAdmin.parent.enable)
- description and source-code
```javascript
function enable(setting) {
  return this.set(setting, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.enabled"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>enabled (setting)](#apidoc.element.node-red.httpAdmin.parent.enabled)
- description and source-code
```javascript
function enabled(setting) {
  return Boolean(this.set(setting));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.engine"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>engine (ext, fn)](#apidoc.element.node-red.httpAdmin.parent.engine)
- description and source-code
```javascript
function engine(ext, fn) {
  if (typeof fn !== 'function') {
    throw new Error('callback function required');
  }

  // get file extension
  var extension = ext[0] !== '.'
    ? '.' + ext
    : ext;

  // store engine
  this.engines[extension] = fn;

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.eventNames"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>eventNames ()](#apidoc.element.node-red.httpAdmin.parent.eventNames)
- description and source-code
```javascript
function eventNames() {
  return this._eventsCount > 0 ? Reflect.ownKeys(this._events) : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.get"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>get (path)](#apidoc.element.node-red.httpAdmin.parent.get)
- description and source-code
```javascript
get = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.getMaxListeners"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>getMaxListeners ()](#apidoc.element.node-red.httpAdmin.parent.getMaxListeners)
- description and source-code
```javascript
function getMaxListeners() {
  return $getMaxListeners(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.handle"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>handle (req, res, callback)](#apidoc.element.node-red.httpAdmin.parent.handle)
- description and source-code
```javascript
function handle(req, res, callback) {
  var router = this._router;

  // final handler
  var done = callback || finalhandler(req, res, {
    env: this.get('env'),
    onerror: logerror.bind(this)
  });

  // no routes
  if (!router) {
    debug('no routes defined on app');
    done();
    return;
  }

  router.handle(req, res, done);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.head"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>head (path)](#apidoc.element.node-red.httpAdmin.parent.head)
- description and source-code
```javascript
head = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.init"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>init ()](#apidoc.element.node-red.httpAdmin.parent.init)
- description and source-code
```javascript
function init() {
  this.cache = {};
  this.engines = {};
  this.settings = {};

  this.defaultConfiguration();
}
```
- example usage
```shell
...
settings.flowFile = flowFile;
}
if (parsedArgs.userDir) {
settings.userDir = parsedArgs.userDir;
}

try {
RED.init(server,settings);
} catch(err) {
if (err.code == "unsupported_version") {
    console.log("Unsupported version of node.js:",process.version);
    console.log("Node-RED requires node.js v4 or later");
} else if  (err.code == "not_built") {
    console.log("Node-RED has not been built. See README.md for details");
} else {
...
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.lazyrouter"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>lazyrouter ()](#apidoc.element.node-red.httpAdmin.parent.lazyrouter)
- description and source-code
```javascript
function lazyrouter() {
  if (!this._router) {
    this._router = new Router({
      caseSensitive: this.enabled('case sensitive routing'),
      strict: this.enabled('strict routing')
    });

    this._router.use(query(this.get('query parser fn')));
    this._router.use(middleware.init(this));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.link"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>link (path)](#apidoc.element.node-red.httpAdmin.parent.link)
- description and source-code
```javascript
link = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.listen"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>listen ()](#apidoc.element.node-red.httpAdmin.parent.listen)
- description and source-code
```javascript
function listen() {
  var server = http.createServer(this);
  return server.listen.apply(server, arguments);
}
```
- example usage
```shell
...
                RED.log.error(err.stack);
            } else {
                RED.log.error(err);
            }
        }
        process.exit(1);
    });
    server.listen(settings.uiPort,settings.uiHost,function() {
        if (settings.httpAdminRoot === false) {
            RED.log.info(RED.log._("server.admin-ui-disabled"));
        }
        process.title = parsedArgs.title || 'node-red';
        RED.log.info(RED.log._("server.now-running", {listenpath:getListenPath()}));
    });
} else {
...
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.listenerCount"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>listenerCount (type)](#apidoc.element.node-red.httpAdmin.parent.listenerCount)
- description and source-code
```javascript
function listenerCount(type) {
  const events = this._events;

  if (events) {
    const evlistener = events[type];

    if (typeof evlistener === 'function') {
      return 1;
    } else if (evlistener) {
      return evlistener.length;
    }
  }

  return 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.listeners"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>listeners (type)](#apidoc.element.node-red.httpAdmin.parent.listeners)
- description and source-code
```javascript
function listeners(type) {
  var evlistener;
  var ret;
  var events = this._events;

  if (!events)
    ret = [];
  else {
    evlistener = events[type];
    if (!evlistener)
      ret = [];
    else if (typeof evlistener === 'function')
      ret = [evlistener];
    else
      ret = arrayClone(evlistener, evlistener.length);
  }

  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.lock"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>lock (path)](#apidoc.element.node-red.httpAdmin.parent.lock)
- description and source-code
```javascript
lock = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.m-search"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>m-search (path)](#apidoc.element.node-red.httpAdmin.parent.m-search)
- description and source-code
```javascript
m-search = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.merge"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>merge (path)](#apidoc.element.node-red.httpAdmin.parent.merge)
- description and source-code
```javascript
merge = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.mkactivity"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>mkactivity (path)](#apidoc.element.node-red.httpAdmin.parent.mkactivity)
- description and source-code
```javascript
mkactivity = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.mkcalendar"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>mkcalendar (path)](#apidoc.element.node-red.httpAdmin.parent.mkcalendar)
- description and source-code
```javascript
mkcalendar = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.mkcol"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>mkcol (path)](#apidoc.element.node-red.httpAdmin.parent.mkcol)
- description and source-code
```javascript
mkcol = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.move"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>move (path)](#apidoc.element.node-red.httpAdmin.parent.move)
- description and source-code
```javascript
move = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.notify"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>notify (path)](#apidoc.element.node-red.httpAdmin.parent.notify)
- description and source-code
```javascript
notify = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.on"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>on (type, listener)](#apidoc.element.node-red.httpAdmin.parent.on)
- description and source-code
```javascript
function addListener(type, listener) {
  return _addListener(this, type, listener, false);
}
```
- example usage
```shell
...
    listenPath += "/";
}
return listenPath;
}

RED.start().then(function() {
if (settings.httpAdminRoot !== false || settings.httpNodeRoot !== false || settings.httpStatic) {
    server.on('error', function(err) {
        if (err.errno === "EADDRINUSE") {
            RED.log.error(RED.log._("server.unable-to-listen", {listenpath:getListenPath()}));
            RED.log.error(RED.log._("server.port-in-use"));
        } else {
            RED.log.error(RED.log._("server.uncaught-exception"));
            if (err.stack) {
                RED.log.error(err.stack);
...
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.once"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>once (type, listener)](#apidoc.element.node-red.httpAdmin.parent.once)
- description and source-code
```javascript
function once(type, listener) {
  if (typeof listener !== 'function')
    throw new TypeError('"listener" argument must be a function');
  this.on(type, _onceWrap(this, type, listener));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.options"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>options (path)](#apidoc.element.node-red.httpAdmin.parent.options)
- description and source-code
```javascript
options = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.param"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>param (name, fn)](#apidoc.element.node-red.httpAdmin.parent.param)
- description and source-code
```javascript
function param(name, fn) {
  this.lazyrouter();

  if (Array.isArray(name)) {
    for (var i = 0; i < name.length; i++) {
      this.param(name[i], fn);
    }

    return this;
  }

  this._router.param(name, fn);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.patch"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>patch (path)](#apidoc.element.node-red.httpAdmin.parent.patch)
- description and source-code
```javascript
patch = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.path"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>path ()](#apidoc.element.node-red.httpAdmin.parent.path)
- description and source-code
```javascript
function path() {
  return this.parent
    ? this.parent.path() + this.mountpath
    : '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.post"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>post (path)](#apidoc.element.node-red.httpAdmin.parent.post)
- description and source-code
```javascript
post = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.prependListener"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>prependListener (type, listener)](#apidoc.element.node-red.httpAdmin.parent.prependListener)
- description and source-code
```javascript
function prependListener(type, listener) {
  return _addListener(this, type, listener, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.prependOnceListener"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>prependOnceListener (type, listener)](#apidoc.element.node-red.httpAdmin.parent.prependOnceListener)
- description and source-code
```javascript
function prependOnceListener(type, listener) {
  if (typeof listener !== 'function')
    throw new TypeError('"listener" argument must be a function');
  this.prependListener(type, _onceWrap(this, type, listener));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.propfind"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>propfind (path)](#apidoc.element.node-red.httpAdmin.parent.propfind)
- description and source-code
```javascript
propfind = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.proppatch"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>proppatch (path)](#apidoc.element.node-red.httpAdmin.parent.proppatch)
- description and source-code
```javascript
proppatch = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.purge"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>purge (path)](#apidoc.element.node-red.httpAdmin.parent.purge)
- description and source-code
```javascript
purge = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.put"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>put (path)](#apidoc.element.node-red.httpAdmin.parent.put)
- description and source-code
```javascript
put = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.rebind"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>rebind (path)](#apidoc.element.node-red.httpAdmin.parent.rebind)
- description and source-code
```javascript
rebind = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.removeAllListeners"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>removeAllListeners (type)](#apidoc.element.node-red.httpAdmin.parent.removeAllListeners)
- description and source-code
```javascript
function removeAllListeners(type) {
  var listeners, events;

  events = this._events;
  if (!events)
    return this;

  // not listening for removeListener, no need to emit
  if (!events.removeListener) {
    if (arguments.length === 0) {
      this._events = new EventHandlers();
      this._eventsCount = 0;
    } else if (events[type]) {
      if (--this._eventsCount === 0)
        this._events = new EventHandlers();
      else
        delete events[type];
    }
    return this;
  }

  // emit removeListener for all listeners on all events
  if (arguments.length === 0) {
    var keys = Object.keys(events);
    for (var i = 0, key; i < keys.length; ++i) {
      key = keys[i];
      if (key === 'removeListener') continue;
      this.removeAllListeners(key);
    }
    this.removeAllListeners('removeListener');
    this._events = new EventHandlers();
    this._eventsCount = 0;
    return this;
  }

  listeners = events[type];

  if (typeof listeners === 'function') {
    this.removeListener(type, listeners);
  } else if (listeners) {
    // LIFO order
    do {
      this.removeListener(type, listeners[listeners.length - 1]);
    } while (listeners[0]);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.removeListener"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>removeListener (type, listener)](#apidoc.element.node-red.httpAdmin.parent.removeListener)
- description and source-code
```javascript
function removeListener(type, listener) {
  var list, events, position, i, originalListener;

  if (typeof listener !== 'function')
    throw new TypeError('"listener" argument must be a function');

  events = this._events;
  if (!events)
    return this;

  list = events[type];
  if (!list)
    return this;

  if (list === listener || list.listener === listener) {
    if (--this._eventsCount === 0)
      this._events = new EventHandlers();
    else {
      delete events[type];
      if (events.removeListener)
        this.emit('removeListener', type, list.listener || listener);
    }
  } else if (typeof list !== 'function') {
    position = -1;

    for (i = list.length; i-- > 0;) {
      if (list[i] === listener || list[i].listener === listener) {
        originalListener = list[i].listener;
        position = i;
        break;
      }
    }

    if (position < 0)
      return this;

    if (list.length === 1) {
      list[0] = undefined;
      if (--this._eventsCount === 0) {
        this._events = new EventHandlers();
        return this;
      } else {
        delete events[type];
      }
    } else {
      spliceOne(list, position);
    }

    if (events.removeListener)
      this.emit('removeListener', type, originalListener || listener);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.render"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>render (name, options, callback)](#apidoc.element.node-red.httpAdmin.parent.render)
- description and source-code
```javascript
function render(name, options, callback) {
  var cache = this.cache;
  var done = callback;
  var engines = this.engines;
  var opts = options;
  var renderOptions = {};
  var view;

  // support callback function as second arg
  if (typeof options === 'function') {
    done = options;
    opts = {};
  }

  // merge app.locals
  merge(renderOptions, this.locals);

  // merge options._locals
  if (opts._locals) {
    merge(renderOptions, opts._locals);
  }

  // merge options
  merge(renderOptions, opts);

  // set .cache unless explicitly provided
  if (renderOptions.cache == null) {
    renderOptions.cache = this.enabled('view cache');
  }

  // primed cache
  if (renderOptions.cache) {
    view = cache[name];
  }

  // view
  if (!view) {
    var View = this.get('view');

    view = new View(name, {
      defaultEngine: this.get('view engine'),
      root: this.get('views'),
      engines: engines
    });

    if (!view.path) {
      var dirs = Array.isArray(view.root) && view.root.length > 1
        ? 'directories "' + view.root.slice(0, -1).join('", "') + '" or "' + view.root[view.root.length - 1] + '"'
        : 'directory "' + view.root + '"'
      var err = new Error('Failed to lookup view "' + name + '" in views ' + dirs);
      err.view = view;
      return done(err);
    }

    // prime the cache
    if (renderOptions.cache) {
      cache[name] = view;
    }
  }

  // render
  tryRender(view, renderOptions, done);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.report"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>report (path)](#apidoc.element.node-red.httpAdmin.parent.report)
- description and source-code
```javascript
report = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.route"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>route (path)](#apidoc.element.node-red.httpAdmin.parent.route)
- description and source-code
```javascript
function route(path) {
  this.lazyrouter();
  return this._router.route(path);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.search"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>search (path)](#apidoc.element.node-red.httpAdmin.parent.search)
- description and source-code
```javascript
search = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.set"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>set (setting, val)](#apidoc.element.node-red.httpAdmin.parent.set)
- description and source-code
```javascript
function set(setting, val) {
  if (arguments.length === 1) {
    // app.get(setting)
    return this.settings[setting];
  }

  debug('set "%s" to %o', setting, val);

  // set value
  this.settings[setting] = val;

  // trigger matched settings
  switch (setting) {
    case 'etag':
      this.set('etag fn', compileETag(val));
      break;
    case 'query parser':
      this.set('query parser fn', compileQueryParser(val));
      break;
    case 'trust proxy':
      this.set('trust proxy fn', compileTrust(val));

      // trust proxy inherit back-compat
      Object.defineProperty(this.settings, trustProxyDefaultSymbol, {
        configurable: true,
        value: false
      });

      break;
  }

  return this;
}
```
- example usage
```shell
...

    return function(req,res,next) {
        if (req.method === 'OPTIONS') {
            return next();
        }
        var requestUser = basicAuth(req);
        if (!requestUser || requestUser.name !== user || !checkPassword(requestUser.pass)) {
            res.set('WWW-Authenticate', 'Basic realm=Authorization Required');
            return res.sendStatus(401);
        }
        next();
    }
}

if (settings.httpAdminRoot !== false && settings.httpAdminAuth) {
...
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.setMaxListeners"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>setMaxListeners (n)](#apidoc.element.node-red.httpAdmin.parent.setMaxListeners)
- description and source-code
```javascript
function setMaxListeners(n) {
  if (typeof n !== 'number' || n < 0 || isNaN(n))
    throw new TypeError('"n" argument must be a positive number');
  this._maxListeners = n;
  return this;
}
```
- example usage
```shell
...
}

if (settings.https) {
server = https.createServer(settings.https,function(req,res) {app(req,res);});
} else {
server = http.createServer(function(req,res) {app(req,res);});
}
server.setMaxListeners(0);

function formatRoot(root) {
if (root[0] != "/") {
    root = "/" + root;
}
if (root.slice(-1) != "/") {
    root = root + "/";
...
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.subscribe"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>subscribe (path)](#apidoc.element.node-red.httpAdmin.parent.subscribe)
- description and source-code
```javascript
subscribe = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.trace"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>trace (path)](#apidoc.element.node-red.httpAdmin.parent.trace)
- description and source-code
```javascript
trace = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.unbind"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>unbind (path)](#apidoc.element.node-red.httpAdmin.parent.unbind)
- description and source-code
```javascript
unbind = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.unlink"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>unlink (path)](#apidoc.element.node-red.httpAdmin.parent.unlink)
- description and source-code
```javascript
unlink = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.unlock"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>unlock (path)](#apidoc.element.node-red.httpAdmin.parent.unlock)
- description and source-code
```javascript
unlock = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.unsubscribe"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>unsubscribe (path)](#apidoc.element.node-red.httpAdmin.parent.unsubscribe)
- description and source-code
```javascript
unsubscribe = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.parent.use"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.parent.</span>use (fn)](#apidoc.element.node-red.httpAdmin.parent.use)
- description and source-code
```javascript
function use(fn) {
  var offset = 0;
  var path = '/';

  // default path to '/'
  // disambiguate app.use([fn])
  if (typeof fn !== 'function') {
    var arg = fn;

    while (Array.isArray(arg) && arg.length !== 0) {
      arg = arg[0];
    }

    // first arg is the path
    if (typeof arg !== 'function') {
      offset = 1;
      path = fn;
    }
  }

  var fns = flatten(slice.call(arguments, offset));

  if (fns.length === 0) {
    throw new TypeError('app.use() requires middleware functions');
  }

  // setup router
  this.lazyrouter();
  var router = this._router;

  fns.forEach(function (fn) {
    // non-express app
    if (!fn || !fn.handle || !fn.set) {
      return router.use(path, fn);
    }

    debug('.use app under %s', path);
    fn.mountpath = path;
    fn.parent = this;

    // restore .app property on req and res
    router.use(path, function mounted_app(req, res, next) {
      var orig = req.app;
      fn.handle(req, res, function (err) {
        req.__proto__ = orig.request;
        res.__proto__ = orig.response;
        next(err);
      });
    });

    // mounted an app
    fn.emit('mount', this);
  }, this);

  return this;
}
```
- example usage
```shell
...
    }
    next();
}
}

if (settings.httpAdminRoot !== false && settings.httpAdminAuth) {
RED.log.warn(RED.log._("server.httpadminauth-deprecated"));
app.use(settings.httpAdminRoot, basicAuthMiddleware(settings.httpAdminAuth.user,settings.httpAdminAuth.pass));
}

if (settings.httpAdminRoot !== false) {
app.use(settings.httpAdminRoot,RED.httpAdmin);
}
if (settings.httpNodeRoot !== false && settings.httpNodeAuth) {
app.use(settings.httpNodeRoot,basicAuthMiddleware(settings.httpNodeAuth.user,settings.httpNodeAuth.pass));
...
```



# <a name="apidoc.module.node-red.httpAdmin.request"></a>[module node-red.httpAdmin.request](#apidoc.module.node-red.httpAdmin.request)

#### <a name="apidoc.element.node-red.httpAdmin.request.app"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.request.</span>app (req, res, next)](#apidoc.element.node-red.httpAdmin.request.app)
- description and source-code
```javascript
app = function (req, res, next) {
  app.handle(req, res, next);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-red.httpAdmin.response"></a>[module node-red.httpAdmin.response](#apidoc.module.node-red.httpAdmin.response)

#### <a name="apidoc.element.node-red.httpAdmin.response.app"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.response.</span>app (req, res, next)](#apidoc.element.node-red.httpAdmin.response.app)
- description and source-code
```javascript
app = function (req, res, next) {
  app.handle(req, res, next);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-red.httpAdmin.settings"></a>[module node-red.httpAdmin.settings](#apidoc.module.node-red.httpAdmin.settings)

#### <a name="apidoc.element.node-red.httpAdmin.settings.view"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.settings.</span>view (name, options)](#apidoc.element.node-red.httpAdmin.settings.view)
- description and source-code
```javascript
function View(name, options) {
  var opts = options || {};

  this.defaultEngine = opts.defaultEngine;
  this.ext = extname(name);
  this.name = name;
  this.root = opts.root;

  if (!this.ext && !this.defaultEngine) {
    throw new Error('No default engine was specified and no extension was provided.');
  }

  var fileName = name;

  if (!this.ext) {
    // get extension from default engine name
    this.ext = this.defaultEngine[0] !== '.'
      ? '.' + this.defaultEngine
      : this.defaultEngine;

    fileName += this.ext;
  }

  if (!opts.engines[this.ext]) {
    // load engine
    opts.engines[this.ext] = require(this.ext.substr(1)).__express;
  }

  // store loaded engine
  this.engine = opts.engines[this.ext];

  // lookup path
  this.path = this.lookup(fileName);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-red.httpAdmin.settings.view.prototype"></a>[module node-red.httpAdmin.settings.view.prototype](#apidoc.module.node-red.httpAdmin.settings.view.prototype)

#### <a name="apidoc.element.node-red.httpAdmin.settings.view.prototype.lookup"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.settings.view.prototype.</span>lookup (name)](#apidoc.element.node-red.httpAdmin.settings.view.prototype.lookup)
- description and source-code
```javascript
function lookup(name) {
  var path;
  var roots = [].concat(this.root);

  debug('lookup "%s"', name);

  for (var i = 0; i < roots.length && !path; i++) {
    var root = roots[i];

    // resolve the path
    var loc = resolve(root, name);
    var dir = dirname(loc);
    var file = basename(loc);

    // resolve the file
    path = this.resolve(dir, file);
  }

  return path;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.settings.view.prototype.render"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.settings.view.prototype.</span>render (options, callback)](#apidoc.element.node-red.httpAdmin.settings.view.prototype.render)
- description and source-code
```javascript
function render(options, callback) {
  debug('render "%s"', this.path);
  this.engine(this.path, options, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpAdmin.settings.view.prototype.resolve"></a>[function <span class="apidocSignatureSpan">node-red.httpAdmin.settings.view.prototype.</span>resolve (dir, file)](#apidoc.element.node-red.httpAdmin.settings.view.prototype.resolve)
- description and source-code
```javascript
function resolve(dir, file) {
  var ext = this.ext;

  // <path>.<ext>
  var path = join(dir, file);
  var stat = tryStat(path);

  if (stat && stat.isFile()) {
    return path;
  }

  // <path>/index.<ext>
  path = join(dir, basename(file, ext), 'index' + ext);
  stat = tryStat(path);

  if (stat && stat.isFile()) {
    return path;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-red.httpNode"></a>[module node-red.httpNode](#apidoc.module.node-red.httpNode)

#### <a name="apidoc.element.node-red.httpNode.httpNode"></a>[function <span class="apidocSignatureSpan">node-red.</span>httpNode (req, res, next)](#apidoc.element.node-red.httpNode.httpNode)
- description and source-code
```javascript
httpNode = function (req, res, next) {
  app.handle(req, res, next);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.acl"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>acl (path)](#apidoc.element.node-red.httpNode.acl)
- description and source-code
```javascript
acl = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.addListener"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>addListener (type, listener)](#apidoc.element.node-red.httpNode.addListener)
- description and source-code
```javascript
function addListener(type, listener) {
  return _addListener(this, type, listener, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.all"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>all (path)](#apidoc.element.node-red.httpNode.all)
- description and source-code
```javascript
function all(path) {
  this.lazyrouter();

  var route = this._router.route(path);
  var args = slice.call(arguments, 1);

  for (var i = 0; i < methods.length; i++) {
    route[methods[i]].apply(route, args);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.bind"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>bind (path)](#apidoc.element.node-red.httpNode.bind)
- description and source-code
```javascript
bind = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.checkout"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>checkout (path)](#apidoc.element.node-red.httpNode.checkout)
- description and source-code
```javascript
checkout = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.connect"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>connect (path)](#apidoc.element.node-red.httpNode.connect)
- description and source-code
```javascript
connect = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.copy"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>copy (path)](#apidoc.element.node-red.httpNode.copy)
- description and source-code
```javascript
copy = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.defaultConfiguration"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>defaultConfiguration ()](#apidoc.element.node-red.httpNode.defaultConfiguration)
- description and source-code
```javascript
function defaultConfiguration() {
  var env = process.env.NODE_ENV || 'development';

  // default settings
  this.enable('x-powered-by');
  this.set('etag', 'weak');
  this.set('env', env);
  this.set('query parser', 'extended');
  this.set('subdomain offset', 2);
  this.set('trust proxy', false);

  // trust proxy inherit back-compat
  Object.defineProperty(this.settings, trustProxyDefaultSymbol, {
    configurable: true,
    value: true
  });

  debug('booting in %s mode', env);

  this.on('mount', function onmount(parent) {
    // inherit trust proxy
    if (this.settings[trustProxyDefaultSymbol] === true
      && typeof parent.settings['trust proxy fn'] === 'function') {
      delete this.settings['trust proxy'];
      delete this.settings['trust proxy fn'];
    }

    // inherit protos
    this.request.__proto__ = parent.request;
    this.response.__proto__ = parent.response;
    this.engines.__proto__ = parent.engines;
    this.settings.__proto__ = parent.settings;
  });

  // setup locals
  this.locals = Object.create(null);

  // top-most app is mounted at /
  this.mountpath = '/';

  // default locals
  this.locals.settings = this.settings;

  // default configuration
  this.set('view', View);
  this.set('views', resolve('views'));
  this.set('jsonp callback name', 'callback');

  if (env === 'production') {
    this.enable('view cache');
  }

  Object.defineProperty(this, 'router', {
    get: function() {
      throw new Error('\'app.router\' is deprecated!\nPlease see the 3.x to 4.x migration guide for details on how to update your
 app.');
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.del"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>del (arg0)](#apidoc.element.node-red.httpNode.del)
- description and source-code
```javascript
del = function (arg0) {
"use strict"
log.call(deprecate, message, site)
return fn.apply(this, arguments)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.delete"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>delete (path)](#apidoc.element.node-red.httpNode.delete)
- description and source-code
```javascript
delete = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.disable"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>disable (setting)](#apidoc.element.node-red.httpNode.disable)
- description and source-code
```javascript
function disable(setting) {
  return this.set(setting, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.disabled"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>disabled (setting)](#apidoc.element.node-red.httpNode.disabled)
- description and source-code
```javascript
function disabled(setting) {
  return !this.set(setting);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.emit"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>emit (type)](#apidoc.element.node-red.httpNode.emit)
- description and source-code
```javascript
function emit(type) {
  var er, handler, len, args, i, events, domain;
  var needDomainExit = false;
  var doError = (type === 'error');

  events = this._events;
  if (events)
    doError = (doError && events.error == null);
  else if (!doError)
    return false;

  domain = this.domain;

  // If there is no 'error' event listener then throw.
  if (doError) {
    er = arguments[1];
    if (domain) {
      if (!er)
        er = new Error('Uncaught, unspecified "error" event');
      er.domainEmitter = this;
      er.domain = domain;
      er.domainThrown = false;
      domain.emit('error', er);
    } else if (er instanceof Error) {
      throw er; // Unhandled 'error' event
    } else {
      // At least give some kind of context to the user
      var err = new Error('Uncaught, unspecified "error" event. (' + er + ')');
      err.context = er;
      throw err;
    }
    return false;
  }

  handler = events[type];

  if (!handler)
    return false;

  if (domain && this !== process) {
    domain.enter();
    needDomainExit = true;
  }

  var isFn = typeof handler === 'function';
  len = arguments.length;
  switch (len) {
    // fast cases
    case 1:
      emitNone(handler, isFn, this);
      break;
    case 2:
      emitOne(handler, isFn, this, arguments[1]);
      break;
    case 3:
      emitTwo(handler, isFn, this, arguments[1], arguments[2]);
      break;
    case 4:
      emitThree(handler, isFn, this, arguments[1], arguments[2], arguments[3]);
      break;
    // slower
    default:
      args = new Array(len - 1);
      for (i = 1; i < len; i++)
        args[i - 1] = arguments[i];
      emitMany(handler, isFn, this, args);
  }

  if (needDomainExit)
    domain.exit();

  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.enable"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>enable (setting)](#apidoc.element.node-red.httpNode.enable)
- description and source-code
```javascript
function enable(setting) {
  return this.set(setting, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.enabled"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>enabled (setting)](#apidoc.element.node-red.httpNode.enabled)
- description and source-code
```javascript
function enabled(setting) {
  return Boolean(this.set(setting));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.engine"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>engine (ext, fn)](#apidoc.element.node-red.httpNode.engine)
- description and source-code
```javascript
function engine(ext, fn) {
  if (typeof fn !== 'function') {
    throw new Error('callback function required');
  }

  // get file extension
  var extension = ext[0] !== '.'
    ? '.' + ext
    : ext;

  // store engine
  this.engines[extension] = fn;

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.eventNames"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>eventNames ()](#apidoc.element.node-red.httpNode.eventNames)
- description and source-code
```javascript
function eventNames() {
  return this._eventsCount > 0 ? Reflect.ownKeys(this._events) : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.get"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>get (path)](#apidoc.element.node-red.httpNode.get)
- description and source-code
```javascript
get = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.getMaxListeners"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>getMaxListeners ()](#apidoc.element.node-red.httpNode.getMaxListeners)
- description and source-code
```javascript
function getMaxListeners() {
  return $getMaxListeners(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.handle"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>handle (req, res, callback)](#apidoc.element.node-red.httpNode.handle)
- description and source-code
```javascript
function handle(req, res, callback) {
  var router = this._router;

  // final handler
  var done = callback || finalhandler(req, res, {
    env: this.get('env'),
    onerror: logerror.bind(this)
  });

  // no routes
  if (!router) {
    debug('no routes defined on app');
    done();
    return;
  }

  router.handle(req, res, done);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.head"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>head (path)](#apidoc.element.node-red.httpNode.head)
- description and source-code
```javascript
head = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.init"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>init ()](#apidoc.element.node-red.httpNode.init)
- description and source-code
```javascript
function init() {
  this.cache = {};
  this.engines = {};
  this.settings = {};

  this.defaultConfiguration();
}
```
- example usage
```shell
...
settings.flowFile = flowFile;
}
if (parsedArgs.userDir) {
settings.userDir = parsedArgs.userDir;
}

try {
RED.init(server,settings);
} catch(err) {
if (err.code == "unsupported_version") {
    console.log("Unsupported version of node.js:",process.version);
    console.log("Node-RED requires node.js v4 or later");
} else if  (err.code == "not_built") {
    console.log("Node-RED has not been built. See README.md for details");
} else {
...
```

#### <a name="apidoc.element.node-red.httpNode.lazyrouter"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>lazyrouter ()](#apidoc.element.node-red.httpNode.lazyrouter)
- description and source-code
```javascript
function lazyrouter() {
  if (!this._router) {
    this._router = new Router({
      caseSensitive: this.enabled('case sensitive routing'),
      strict: this.enabled('strict routing')
    });

    this._router.use(query(this.get('query parser fn')));
    this._router.use(middleware.init(this));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.link"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>link (path)](#apidoc.element.node-red.httpNode.link)
- description and source-code
```javascript
link = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.listen"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>listen ()](#apidoc.element.node-red.httpNode.listen)
- description and source-code
```javascript
function listen() {
  var server = http.createServer(this);
  return server.listen.apply(server, arguments);
}
```
- example usage
```shell
...
                RED.log.error(err.stack);
            } else {
                RED.log.error(err);
            }
        }
        process.exit(1);
    });
    server.listen(settings.uiPort,settings.uiHost,function() {
        if (settings.httpAdminRoot === false) {
            RED.log.info(RED.log._("server.admin-ui-disabled"));
        }
        process.title = parsedArgs.title || 'node-red';
        RED.log.info(RED.log._("server.now-running", {listenpath:getListenPath()}));
    });
} else {
...
```

#### <a name="apidoc.element.node-red.httpNode.listenerCount"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>listenerCount (type)](#apidoc.element.node-red.httpNode.listenerCount)
- description and source-code
```javascript
function listenerCount(type) {
  const events = this._events;

  if (events) {
    const evlistener = events[type];

    if (typeof evlistener === 'function') {
      return 1;
    } else if (evlistener) {
      return evlistener.length;
    }
  }

  return 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.listeners"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>listeners (type)](#apidoc.element.node-red.httpNode.listeners)
- description and source-code
```javascript
function listeners(type) {
  var evlistener;
  var ret;
  var events = this._events;

  if (!events)
    ret = [];
  else {
    evlistener = events[type];
    if (!evlistener)
      ret = [];
    else if (typeof evlistener === 'function')
      ret = [evlistener];
    else
      ret = arrayClone(evlistener, evlistener.length);
  }

  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.lock"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>lock (path)](#apidoc.element.node-red.httpNode.lock)
- description and source-code
```javascript
lock = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.m-search"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>m-search (path)](#apidoc.element.node-red.httpNode.m-search)
- description and source-code
```javascript
m-search = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.merge"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>merge (path)](#apidoc.element.node-red.httpNode.merge)
- description and source-code
```javascript
merge = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.mkactivity"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>mkactivity (path)](#apidoc.element.node-red.httpNode.mkactivity)
- description and source-code
```javascript
mkactivity = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.mkcalendar"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>mkcalendar (path)](#apidoc.element.node-red.httpNode.mkcalendar)
- description and source-code
```javascript
mkcalendar = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.mkcol"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>mkcol (path)](#apidoc.element.node-red.httpNode.mkcol)
- description and source-code
```javascript
mkcol = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.move"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>move (path)](#apidoc.element.node-red.httpNode.move)
- description and source-code
```javascript
move = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.notify"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>notify (path)](#apidoc.element.node-red.httpNode.notify)
- description and source-code
```javascript
notify = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.on"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>on (type, listener)](#apidoc.element.node-red.httpNode.on)
- description and source-code
```javascript
function addListener(type, listener) {
  return _addListener(this, type, listener, false);
}
```
- example usage
```shell
...
    listenPath += "/";
}
return listenPath;
}

RED.start().then(function() {
if (settings.httpAdminRoot !== false || settings.httpNodeRoot !== false || settings.httpStatic) {
    server.on('error', function(err) {
        if (err.errno === "EADDRINUSE") {
            RED.log.error(RED.log._("server.unable-to-listen", {listenpath:getListenPath()}));
            RED.log.error(RED.log._("server.port-in-use"));
        } else {
            RED.log.error(RED.log._("server.uncaught-exception"));
            if (err.stack) {
                RED.log.error(err.stack);
...
```

#### <a name="apidoc.element.node-red.httpNode.once"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>once (type, listener)](#apidoc.element.node-red.httpNode.once)
- description and source-code
```javascript
function once(type, listener) {
  if (typeof listener !== 'function')
    throw new TypeError('"listener" argument must be a function');
  this.on(type, _onceWrap(this, type, listener));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.options"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>options (path)](#apidoc.element.node-red.httpNode.options)
- description and source-code
```javascript
options = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.param"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>param (name, fn)](#apidoc.element.node-red.httpNode.param)
- description and source-code
```javascript
function param(name, fn) {
  this.lazyrouter();

  if (Array.isArray(name)) {
    for (var i = 0; i < name.length; i++) {
      this.param(name[i], fn);
    }

    return this;
  }

  this._router.param(name, fn);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.parent"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>parent (req, res, next)](#apidoc.element.node-red.httpNode.parent)
- description and source-code
```javascript
parent = function (req, res, next) {
  app.handle(req, res, next);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.patch"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>patch (path)](#apidoc.element.node-red.httpNode.patch)
- description and source-code
```javascript
patch = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.path"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>path ()](#apidoc.element.node-red.httpNode.path)
- description and source-code
```javascript
function path() {
  return this.parent
    ? this.parent.path() + this.mountpath
    : '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.post"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>post (path)](#apidoc.element.node-red.httpNode.post)
- description and source-code
```javascript
post = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.prependListener"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>prependListener (type, listener)](#apidoc.element.node-red.httpNode.prependListener)
- description and source-code
```javascript
function prependListener(type, listener) {
  return _addListener(this, type, listener, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.prependOnceListener"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>prependOnceListener (type, listener)](#apidoc.element.node-red.httpNode.prependOnceListener)
- description and source-code
```javascript
function prependOnceListener(type, listener) {
  if (typeof listener !== 'function')
    throw new TypeError('"listener" argument must be a function');
  this.prependListener(type, _onceWrap(this, type, listener));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.propfind"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>propfind (path)](#apidoc.element.node-red.httpNode.propfind)
- description and source-code
```javascript
propfind = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.proppatch"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>proppatch (path)](#apidoc.element.node-red.httpNode.proppatch)
- description and source-code
```javascript
proppatch = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.purge"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>purge (path)](#apidoc.element.node-red.httpNode.purge)
- description and source-code
```javascript
purge = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.put"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>put (path)](#apidoc.element.node-red.httpNode.put)
- description and source-code
```javascript
put = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.rebind"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>rebind (path)](#apidoc.element.node-red.httpNode.rebind)
- description and source-code
```javascript
rebind = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.removeAllListeners"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>removeAllListeners (type)](#apidoc.element.node-red.httpNode.removeAllListeners)
- description and source-code
```javascript
function removeAllListeners(type) {
  var listeners, events;

  events = this._events;
  if (!events)
    return this;

  // not listening for removeListener, no need to emit
  if (!events.removeListener) {
    if (arguments.length === 0) {
      this._events = new EventHandlers();
      this._eventsCount = 0;
    } else if (events[type]) {
      if (--this._eventsCount === 0)
        this._events = new EventHandlers();
      else
        delete events[type];
    }
    return this;
  }

  // emit removeListener for all listeners on all events
  if (arguments.length === 0) {
    var keys = Object.keys(events);
    for (var i = 0, key; i < keys.length; ++i) {
      key = keys[i];
      if (key === 'removeListener') continue;
      this.removeAllListeners(key);
    }
    this.removeAllListeners('removeListener');
    this._events = new EventHandlers();
    this._eventsCount = 0;
    return this;
  }

  listeners = events[type];

  if (typeof listeners === 'function') {
    this.removeListener(type, listeners);
  } else if (listeners) {
    // LIFO order
    do {
      this.removeListener(type, listeners[listeners.length - 1]);
    } while (listeners[0]);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.removeListener"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>removeListener (type, listener)](#apidoc.element.node-red.httpNode.removeListener)
- description and source-code
```javascript
function removeListener(type, listener) {
  var list, events, position, i, originalListener;

  if (typeof listener !== 'function')
    throw new TypeError('"listener" argument must be a function');

  events = this._events;
  if (!events)
    return this;

  list = events[type];
  if (!list)
    return this;

  if (list === listener || list.listener === listener) {
    if (--this._eventsCount === 0)
      this._events = new EventHandlers();
    else {
      delete events[type];
      if (events.removeListener)
        this.emit('removeListener', type, list.listener || listener);
    }
  } else if (typeof list !== 'function') {
    position = -1;

    for (i = list.length; i-- > 0;) {
      if (list[i] === listener || list[i].listener === listener) {
        originalListener = list[i].listener;
        position = i;
        break;
      }
    }

    if (position < 0)
      return this;

    if (list.length === 1) {
      list[0] = undefined;
      if (--this._eventsCount === 0) {
        this._events = new EventHandlers();
        return this;
      } else {
        delete events[type];
      }
    } else {
      spliceOne(list, position);
    }

    if (events.removeListener)
      this.emit('removeListener', type, originalListener || listener);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.render"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>render (name, options, callback)](#apidoc.element.node-red.httpNode.render)
- description and source-code
```javascript
function render(name, options, callback) {
  var cache = this.cache;
  var done = callback;
  var engines = this.engines;
  var opts = options;
  var renderOptions = {};
  var view;

  // support callback function as second arg
  if (typeof options === 'function') {
    done = options;
    opts = {};
  }

  // merge app.locals
  merge(renderOptions, this.locals);

  // merge options._locals
  if (opts._locals) {
    merge(renderOptions, opts._locals);
  }

  // merge options
  merge(renderOptions, opts);

  // set .cache unless explicitly provided
  if (renderOptions.cache == null) {
    renderOptions.cache = this.enabled('view cache');
  }

  // primed cache
  if (renderOptions.cache) {
    view = cache[name];
  }

  // view
  if (!view) {
    var View = this.get('view');

    view = new View(name, {
      defaultEngine: this.get('view engine'),
      root: this.get('views'),
      engines: engines
    });

    if (!view.path) {
      var dirs = Array.isArray(view.root) && view.root.length > 1
        ? 'directories "' + view.root.slice(0, -1).join('", "') + '" or "' + view.root[view.root.length - 1] + '"'
        : 'directory "' + view.root + '"'
      var err = new Error('Failed to lookup view "' + name + '" in views ' + dirs);
      err.view = view;
      return done(err);
    }

    // prime the cache
    if (renderOptions.cache) {
      cache[name] = view;
    }
  }

  // render
  tryRender(view, renderOptions, done);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.report"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>report (path)](#apidoc.element.node-red.httpNode.report)
- description and source-code
```javascript
report = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.route"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>route (path)](#apidoc.element.node-red.httpNode.route)
- description and source-code
```javascript
function route(path) {
  this.lazyrouter();
  return this._router.route(path);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.search"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>search (path)](#apidoc.element.node-red.httpNode.search)
- description and source-code
```javascript
search = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.set"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>set (setting, val)](#apidoc.element.node-red.httpNode.set)
- description and source-code
```javascript
function set(setting, val) {
  if (arguments.length === 1) {
    // app.get(setting)
    return this.settings[setting];
  }

  debug('set "%s" to %o', setting, val);

  // set value
  this.settings[setting] = val;

  // trigger matched settings
  switch (setting) {
    case 'etag':
      this.set('etag fn', compileETag(val));
      break;
    case 'query parser':
      this.set('query parser fn', compileQueryParser(val));
      break;
    case 'trust proxy':
      this.set('trust proxy fn', compileTrust(val));

      // trust proxy inherit back-compat
      Object.defineProperty(this.settings, trustProxyDefaultSymbol, {
        configurable: true,
        value: false
      });

      break;
  }

  return this;
}
```
- example usage
```shell
...

    return function(req,res,next) {
        if (req.method === 'OPTIONS') {
            return next();
        }
        var requestUser = basicAuth(req);
        if (!requestUser || requestUser.name !== user || !checkPassword(requestUser.pass)) {
            res.set('WWW-Authenticate', 'Basic realm=Authorization Required');
            return res.sendStatus(401);
        }
        next();
    }
}

if (settings.httpAdminRoot !== false && settings.httpAdminAuth) {
...
```

#### <a name="apidoc.element.node-red.httpNode.setMaxListeners"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>setMaxListeners (n)](#apidoc.element.node-red.httpNode.setMaxListeners)
- description and source-code
```javascript
function setMaxListeners(n) {
  if (typeof n !== 'number' || n < 0 || isNaN(n))
    throw new TypeError('"n" argument must be a positive number');
  this._maxListeners = n;
  return this;
}
```
- example usage
```shell
...
}

if (settings.https) {
server = https.createServer(settings.https,function(req,res) {app(req,res);});
} else {
server = http.createServer(function(req,res) {app(req,res);});
}
server.setMaxListeners(0);

function formatRoot(root) {
if (root[0] != "/") {
    root = "/" + root;
}
if (root.slice(-1) != "/") {
    root = root + "/";
...
```

#### <a name="apidoc.element.node-red.httpNode.subscribe"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>subscribe (path)](#apidoc.element.node-red.httpNode.subscribe)
- description and source-code
```javascript
subscribe = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.trace"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>trace (path)](#apidoc.element.node-red.httpNode.trace)
- description and source-code
```javascript
trace = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.unbind"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>unbind (path)](#apidoc.element.node-red.httpNode.unbind)
- description and source-code
```javascript
unbind = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.unlink"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>unlink (path)](#apidoc.element.node-red.httpNode.unlink)
- description and source-code
```javascript
unlink = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.unlock"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>unlock (path)](#apidoc.element.node-red.httpNode.unlock)
- description and source-code
```javascript
unlock = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.unsubscribe"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>unsubscribe (path)](#apidoc.element.node-red.httpNode.unsubscribe)
- description and source-code
```javascript
unsubscribe = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.httpNode.use"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.</span>use (fn)](#apidoc.element.node-red.httpNode.use)
- description and source-code
```javascript
function use(fn) {
  var offset = 0;
  var path = '/';

  // default path to '/'
  // disambiguate app.use([fn])
  if (typeof fn !== 'function') {
    var arg = fn;

    while (Array.isArray(arg) && arg.length !== 0) {
      arg = arg[0];
    }

    // first arg is the path
    if (typeof arg !== 'function') {
      offset = 1;
      path = fn;
    }
  }

  var fns = flatten(slice.call(arguments, offset));

  if (fns.length === 0) {
    throw new TypeError('app.use() requires middleware functions');
  }

  // setup router
  this.lazyrouter();
  var router = this._router;

  fns.forEach(function (fn) {
    // non-express app
    if (!fn || !fn.handle || !fn.set) {
      return router.use(path, fn);
    }

    debug('.use app under %s', path);
    fn.mountpath = path;
    fn.parent = this;

    // restore .app property on req and res
    router.use(path, function mounted_app(req, res, next) {
      var orig = req.app;
      fn.handle(req, res, function (err) {
        req.__proto__ = orig.request;
        res.__proto__ = orig.response;
        next(err);
      });
    });

    // mounted an app
    fn.emit('mount', this);
  }, this);

  return this;
}
```
- example usage
```shell
...
    }
    next();
}
}

if (settings.httpAdminRoot !== false && settings.httpAdminAuth) {
RED.log.warn(RED.log._("server.httpadminauth-deprecated"));
app.use(settings.httpAdminRoot, basicAuthMiddleware(settings.httpAdminAuth.user,settings.httpAdminAuth.pass));
}

if (settings.httpAdminRoot !== false) {
app.use(settings.httpAdminRoot,RED.httpAdmin);
}
if (settings.httpNodeRoot !== false && settings.httpNodeAuth) {
app.use(settings.httpNodeRoot,basicAuthMiddleware(settings.httpNodeAuth.user,settings.httpNodeAuth.pass));
...
```



# <a name="apidoc.module.node-red.httpNode._events"></a>[module node-red.httpNode._events](#apidoc.module.node-red.httpNode._events)

#### <a name="apidoc.element.node-red.httpNode._events.mount"></a>[function <span class="apidocSignatureSpan">node-red.httpNode._events.</span>mount (parent)](#apidoc.element.node-red.httpNode._events.mount)
- description and source-code
```javascript
function onmount(parent) {
  // inherit trust proxy
  if (this.settings[trustProxyDefaultSymbol] === true
    && typeof parent.settings['trust proxy fn'] === 'function') {
    delete this.settings['trust proxy'];
    delete this.settings['trust proxy fn'];
  }

  // inherit protos
  this.request.__proto__ = parent.request;
  this.response.__proto__ = parent.response;
  this.engines.__proto__ = parent.engines;
  this.settings.__proto__ = parent.settings;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-red.httpNode.request"></a>[module node-red.httpNode.request](#apidoc.module.node-red.httpNode.request)

#### <a name="apidoc.element.node-red.httpNode.request.app"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.request.</span>app (req, res, next)](#apidoc.element.node-red.httpNode.request.app)
- description and source-code
```javascript
app = function (req, res, next) {
  app.handle(req, res, next);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-red.httpNode.response"></a>[module node-red.httpNode.response](#apidoc.module.node-red.httpNode.response)

#### <a name="apidoc.element.node-red.httpNode.response.app"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.response.</span>app (req, res, next)](#apidoc.element.node-red.httpNode.response.app)
- description and source-code
```javascript
app = function (req, res, next) {
  app.handle(req, res, next);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-red.httpNode.settings"></a>[module node-red.httpNode.settings](#apidoc.module.node-red.httpNode.settings)

#### <a name="apidoc.element.node-red.httpNode.settings.view"></a>[function <span class="apidocSignatureSpan">node-red.httpNode.settings.</span>view (name, options)](#apidoc.element.node-red.httpNode.settings.view)
- description and source-code
```javascript
function View(name, options) {
  var opts = options || {};

  this.defaultEngine = opts.defaultEngine;
  this.ext = extname(name);
  this.name = name;
  this.root = opts.root;

  if (!this.ext && !this.defaultEngine) {
    throw new Error('No default engine was specified and no extension was provided.');
  }

  var fileName = name;

  if (!this.ext) {
    // get extension from default engine name
    this.ext = this.defaultEngine[0] !== '.'
      ? '.' + this.defaultEngine
      : this.defaultEngine;

    fileName += this.ext;
  }

  if (!opts.engines[this.ext]) {
    // load engine
    opts.engines[this.ext] = require(this.ext.substr(1)).__express;
  }

  // store loaded engine
  this.engine = opts.engines[this.ext];

  // lookup path
  this.path = this.lookup(fileName);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-red.library"></a>[module node-red.library](#apidoc.module.node-red.library)

#### <a name="apidoc.element.node-red.library.register"></a>[function <span class="apidocSignatureSpan">node-red.library.</span>register (type)](#apidoc.element.node-red.library.register)
- description and source-code
```javascript
function createLibrary(type) {
    if (redApp) {
        redApp.get(new RegExp("/library/"+type+"($|\/(.*))"),needsPermission("library.read"),function(req,res) {
            var path = req.params[1]||"";
            storage.getLibraryEntry(type,path).then(function(result) {
                log.audit({event: "library.get",type:type},req);
                if (typeof result === "string") {
                    res.writeHead(200, {'Content-Type': 'text/plain'});
                    res.write(result);
                    res.end();
                } else {
                    res.json(result);
                }
            }).otherwise(function(err) {
                if (err) {
                    log.warn(log._("api.library.error-load-entry",{path:path,message:err.toString()}));
                    if (err.code === 'forbidden') {
                        log.audit({event: "library.get",type:type,error:"forbidden"},req);
                        res.status(403).end();
                        return;
                    }
                }
                log.audit({event: "library.get",type:type,error:"not_found"},req);
                res.status(404).end();
            });
        });

        redApp.post(new RegExp("/library/"+type+"\/(.*)"),needsPermission("library.write"),function(req,res) {
            var path = req.params[0];
            var meta = req.body;
            var text = meta.text;
            delete meta.text;

            storage.saveLibraryEntry(type,path,meta,text).then(function() {
                log.audit({event: "library.set",type:type},req);
                res.status(204).end();
            }).otherwise(function(err) {
                log.warn(log._("api.library.error-save-entry",{path:path,message:err.toString()}));
                    if (err.code === 'forbidden') {
                    log.audit({event: "library.set",type:type,error:"forbidden"},req);
                    res.status(403).end();
                    return;
                }
                log.audit({event: "library.set",type:type,error:"unexpected_error",message:err.toString()},req);
                res.status(500).json({error:"unexpected_error", message:err.toString()});
            });
        });
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-red.log"></a>[module node-red.log](#apidoc.module.node-red.log)

#### <a name="apidoc.element.node-red.log.log"></a>[function <span class="apidocSignatureSpan">node-red.</span>log (msg)](#apidoc.element.node-red.log.log)
- description and source-code
```javascript
log = function (msg) {
    msg.timestamp = Date.now();
    logHandlers.forEach(function(handler) {
        handler.emit("log",msg);
    });
}
```
- example usage
```shell
...
// As we want to reserve -t for now, adding a shorthand to help so it
// doesn't get treated as --title
"t":["--help"],
"u":["--userDir"],
"v":["--verbose"]
};
nopt.invalidHandler = function(k,v,t) {
// TODO: console.log(k,v,t);
}

var parsedArgs = nopt(knownOpts,shortHands,process.argv,2)

if (parsedArgs.help) {
console.log("Node-RED v"+RED.version());
console.log("Usage: node-red [-v] [-?] [--settings settings.js] [--userDir DIR]");
...
```

#### <a name="apidoc.element.node-red.log._"></a>[function <span class="apidocSignatureSpan">node-red.log.</span>_ ()](#apidoc.element.node-red.log._)
- description and source-code
```javascript
_ = function () {
    //var opts = {};
    //if (def) {
    //    opts.defaultValue = def;
    //}
    //console.log(arguments);
    return i18n.t.apply(null,arguments);
}
```
- example usage
```shell
...
            return res.sendStatus(401);
        }
        next();
    }
}

if (settings.httpAdminRoot !== false && settings.httpAdminAuth) {
    RED.log.warn(RED.log._("server.httpadminauth-deprecated"));
    app.use(settings.httpAdminRoot, basicAuthMiddleware(settings.httpAdminAuth.user,settings.httpAdminAuth.pass));
}

if (settings.httpAdminRoot !== false) {
    app.use(settings.httpAdminRoot,RED.httpAdmin);
}
if (settings.httpNodeRoot !== false && settings.httpNodeAuth) {
...
```

#### <a name="apidoc.element.node-red.log.addHandler"></a>[function <span class="apidocSignatureSpan">node-red.log.</span>addHandler (func)](#apidoc.element.node-red.log.addHandler)
- description and source-code
```javascript
addHandler = function (func) {
    logHandlers.push(func);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.log.audit"></a>[function <span class="apidocSignatureSpan">node-red.log.</span>audit (msg, req)](#apidoc.element.node-red.log.audit)
- description and source-code
```javascript
audit = function (msg, req) {
    msg.level = log.AUDIT;
    if (req) {
        msg.user = req.user;
        msg.path = req.path;
        msg.ip = (req.headers && req.headers['x-forwarded-for']) || (req.connection && req.connection.remoteAddress) || undefined
;
    }
    log.log(msg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.log.debug"></a>[function <span class="apidocSignatureSpan">node-red.log.</span>debug (msg)](#apidoc.element.node-red.log.debug)
- description and source-code
```javascript
debug = function (msg) {
    log.log({level:log.DEBUG,msg:msg});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.log.error"></a>[function <span class="apidocSignatureSpan">node-red.log.</span>error (msg)](#apidoc.element.node-red.log.error)
- description and source-code
```javascript
error = function (msg) {
    log.log({level:log.ERROR,msg:msg});
}
```
- example usage
```shell
...
return listenPath;
}

RED.start().then(function() {
if (settings.httpAdminRoot !== false || settings.httpNodeRoot !== false || settings.httpStatic) {
    server.on('error', function(err) {
        if (err.errno === "EADDRINUSE") {
            RED.log.error(RED.log._("server.unable-to-listen", {listenpath:getListenPath()}));
            RED.log.error(RED.log._("server.port-in-use"));
        } else {
            RED.log.error(RED.log._("server.uncaught-exception"));
            if (err.stack) {
                RED.log.error(err.stack);
            } else {
                RED.log.error(err);
...
```

#### <a name="apidoc.element.node-red.log.info"></a>[function <span class="apidocSignatureSpan">node-red.log.</span>info (msg)](#apidoc.element.node-red.log.info)
- description and source-code
```javascript
info = function (msg) {
    log.log({level:log.INFO,msg:msg});
}
```
- example usage
```shell
...
                RED.log.error(err);
            }
        }
        process.exit(1);
    });
    server.listen(settings.uiPort,settings.uiHost,function() {
        if (settings.httpAdminRoot === false) {
            RED.log.info(RED.log._("server.admin-ui-disabled"));
        }
        process.title = parsedArgs.title || 'node-red';
        RED.log.info(RED.log._("server.now-running", {listenpath:getListenPath()}));
    });
} else {
    RED.log.info(RED.log._("server.headless-mode"));
}
...
```

#### <a name="apidoc.element.node-red.log.init"></a>[function <span class="apidocSignatureSpan">node-red.log.</span>init (settings)](#apidoc.element.node-red.log.init)
- description and source-code
```javascript
init = function (settings) {
    metricsEnabled = false;
    logHandlers = [];
    var loggerSettings = {};
    if (settings.logging) {
        var keys = Object.keys(settings.logging);
        if (keys.length === 0) {
            log.addHandler(new LogHandler());
        } else {
            for (var i=0, l=keys.length; i<l; i++) {
                var config = settings.logging[keys[i]];
                loggerSettings = config || {};
                if ((keys[i] === "console") || config.handler) {
                    log.addHandler(new LogHandler(loggerSettings));
                }
            }
        }
    } else {
        log.addHandler(new LogHandler());
    }
}
```
- example usage
```shell
...
settings.flowFile = flowFile;
}
if (parsedArgs.userDir) {
settings.userDir = parsedArgs.userDir;
}

try {
RED.init(server,settings);
} catch(err) {
if (err.code == "unsupported_version") {
    console.log("Unsupported version of node.js:",process.version);
    console.log("Node-RED requires node.js v4 or later");
} else if  (err.code == "not_built") {
    console.log("Node-RED has not been built. See README.md for details");
} else {
...
```

#### <a name="apidoc.element.node-red.log.metric"></a>[function <span class="apidocSignatureSpan">node-red.log.</span>metric ()](#apidoc.element.node-red.log.metric)
- description and source-code
```javascript
metric = function () {
    return metricsEnabled;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.log.removeHandler"></a>[function <span class="apidocSignatureSpan">node-red.log.</span>removeHandler (func)](#apidoc.element.node-red.log.removeHandler)
- description and source-code
```javascript
removeHandler = function (func) {
    var index = logHandlers.indexOf(func);
    if (index > -1) {
        logHandlers.splice(index,1);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.log.trace"></a>[function <span class="apidocSignatureSpan">node-red.log.</span>trace (msg)](#apidoc.element.node-red.log.trace)
- description and source-code
```javascript
trace = function (msg) {
    log.log({level:log.TRACE,msg:msg});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.log.warn"></a>[function <span class="apidocSignatureSpan">node-red.log.</span>warn (msg)](#apidoc.element.node-red.log.warn)
- description and source-code
```javascript
warn = function (msg) {
    log.log({level:log.WARN,msg:msg});
}
```
- example usage
```shell
...
            return res.sendStatus(401);
        }
        next();
    }
}

if (settings.httpAdminRoot !== false && settings.httpAdminAuth) {
    RED.log.warn(RED.log._("server.httpadminauth-deprecated"));
    app.use(settings.httpAdminRoot, basicAuthMiddleware(settings.httpAdminAuth.user,settings.httpAdminAuth.pass));
}

if (settings.httpAdminRoot !== false) {
    app.use(settings.httpAdminRoot,RED.httpAdmin);
}
if (settings.httpNodeRoot !== false && settings.httpNodeAuth) {
...
```



# <a name="apidoc.module.node-red.nodes"></a>[module node-red.nodes](#apidoc.module.node-red.nodes)

#### <a name="apidoc.element.node-red.nodes.addCredentials"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>addCredentials (id, creds)](#apidoc.element.node-red.nodes.addCredentials)
- description and source-code
```javascript
addCredentials = function (id, creds) {
    if (!credentialCache.hasOwnProperty(id) || JSON.stringify(creds) !== JSON.stringify(credentialCache[id])) {
        credentialCache[id] = creds;
        dirty = true;
    }
    return when.resolve();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.addFlow"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>addFlow (flow)](#apidoc.element.node-red.nodes.addFlow)
- description and source-code
```javascript
function addFlow(flow) {
    var i,node;
    if (!flow.hasOwnProperty('nodes')) {
        throw new Error('missing nodes property');
    }
    flow.id = redUtil.generateId();

    var nodes = [{
        type:'tab',
        label:flow.label,
        id:flow.id
    }];

    for (i=0;i<flow.nodes.length;i++) {
        node = flow.nodes[i];
        if (activeFlowConfig.allNodes[node.id]) {
            // TODO nls
            return when.reject(new Error('duplicate id'));
        }
        if (node.type === 'tab' || node.type === 'subflow') {
            return when.reject(new Error('invalid node type: '+node.type));
        }
        node.z = flow.id;
        nodes.push(node);
    }
    if (flow.configs) {
        for (i=0;i<flow.configs.length;i++) {
            node = flow.configs[i];
            if (activeFlowConfig.allNodes[node.id]) {
                // TODO nls
                return when.reject(new Error('duplicate id'));
            }
            if (node.type === 'tab' || node.type === 'subflow') {
                return when.reject(new Error('invalid node type: '+node.type));
            }
            node.z = flow.id;
            nodes.push(node);
        }
    }
    var newConfig = clone(activeConfig.flows);
    newConfig = newConfig.concat(nodes);

    return setFlows(newConfig,'flows',true).then(function() {
        log.info(log._("nodes.flows.added-flow",{label:(flow.label?flow.label+" ":"")+"["+flow.id+"]"}));
        return flow.id;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.cleanModuleList"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>cleanModuleList ()](#apidoc.element.node-red.nodes.cleanModuleList)
- description and source-code
```javascript
function cleanModuleList() {
    var removed = false;
    for (var mod in moduleConfigs) {
<span class="apidocCodeCommentSpan">        /* istanbul ignore else */
</span>        if (moduleConfigs.hasOwnProperty(mod)) {
            var nodes = moduleConfigs[mod].nodes;
            var node;
            if (mod == "node-red") {
                // For core nodes, look for nodes that are enabled, !loaded and !errored
                for (node in nodes) {
                    /* istanbul ignore else */
                    if (nodes.hasOwnProperty(node)) {
                        var n = nodes[node];
                        if (n.enabled && !n.err && !n.loaded) {
                            removeNode(mod+"/"+node);
                            removed = true;
                        }
                    }
                }
            } else {
                if (moduleConfigs[mod] && !moduleNodes[mod]) {
                    // For node modules, look for missing ones
                    for (node in nodes) {
                        /* istanbul ignore else */
                        if (nodes.hasOwnProperty(node)) {
                            removeNode(mod+"/"+node);
                            removed = true;
                        }
                    }
                    delete moduleConfigs[mod];
                }
            }
        }
    }
    if (removed) {
        saveNodeList();
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.clearRegistry"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>clearRegistry ()](#apidoc.element.node-red.nodes.clearRegistry)
- description and source-code
```javascript
function clear() {
    nodeConfigCache = null;
    moduleConfigs = {};
    nodeList = [];
    nodeConstructors = {};
    nodeTypeToId = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.createNode"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>createNode (node, def)](#apidoc.element.node-red.nodes.createNode)
- description and source-code
```javascript
function createNode(node, def) {
    Node.call(node,def);
    var id = node.id;
    if (def._alias) {
        id = def._alias;
    }
    var creds = credentials.get(id);
    if (creds) {
        //console.log("Attaching credentials to ",node.id);
        // allow $(foo) syntax to substitute env variables for credentials also...
        for (var p in creds) {
            if (creds.hasOwnProperty(p)) {
                flowUtil.mapEnvVarProperties(creds,p);
            }
        }
        node.credentials = creds;
    } else if (credentials.getDefinition(node.type)) {
        node.credentials = {};
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.deleteCredentials"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>deleteCredentials (id)](#apidoc.element.node-red.nodes.deleteCredentials)
- description and source-code
```javascript
deleteCredentials = function (id) {
    delete credentialCache[id];
    dirty = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.disableNode"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>disableNode (id)](#apidoc.element.node-red.nodes.disableNode)
- description and source-code
```javascript
function disableNode(id) {
    flows.checkTypeInUse(id);
    return registry.disableNode(id);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.eachNode"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>eachNode (cb)](#apidoc.element.node-red.nodes.eachNode)
- description and source-code
```javascript
function eachNode(cb) {
    for (var id in activeFlowConfig.allNodes) {
        if (activeFlowConfig.allNodes.hasOwnProperty(id)) {
            cb(activeFlowConfig.allNodes[id]);
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.enableNode"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>enableNode (typeOrId)](#apidoc.element.node-red.nodes.enableNode)
- description and source-code
```javascript
function enableNodeSet(typeOrId) {
    return registry.enableNodeSet(typeOrId).then(function() {
        var nodeSet = registry.getNodeInfo(typeOrId);
        if (!nodeSet.loaded) {
            return loader.loadNodeSet(registry.getFullNodeInfo(typeOrId)).then(function() {
                return registry.getNodeInfo(typeOrId);
            });
        }
        return when.resolve(nodeSet);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.getCredentialDefinition"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>getCredentialDefinition (type)](#apidoc.element.node-red.nodes.getCredentialDefinition)
- description and source-code
```javascript
getCredentialDefinition = function (type) {
    return credentialsDef[type];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.getCredentials"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>getCredentials (id)](#apidoc.element.node-red.nodes.getCredentials)
- description and source-code
```javascript
getCredentials = function (id) {
    return credentialCache[id];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.getFlow"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>getFlow (id)](#apidoc.element.node-red.nodes.getFlow)
- description and source-code
```javascript
function getFlow(id) {
    var flow;
    if (id === 'global') {
        flow = activeFlowConfig;
    } else {
        flow = activeFlowConfig.flows[id];
    }
    if (!flow) {
        return null;
    }
    var result = {
        id: id
    };
    if (flow.label) {
        result.label = flow.label;
    }
    if (id !== 'global') {
        result.nodes = [];
    }
    if (flow.nodes) {
        var nodeIds = Object.keys(flow.nodes);
        if (nodeIds.length > 0) {
            result.nodes = nodeIds.map(function(nodeId) {
                var node = clone(flow.nodes[nodeId]);
                if (node.type === 'link out') {
                    delete node.wires;
                }
                return node;
            })
        }
    }
    if (flow.configs) {
        var configIds = Object.keys(flow.configs);
        result.configs = configIds.map(function(configId) {
            return clone(flow.configs[configId]);
        })
        if (result.configs.length === 0) {
            delete result.configs;
        }
    }
    if (flow.subflows) {
        var subflowIds = Object.keys(flow.subflows);
        result.subflows = subflowIds.map(function(subflowId) {
            var subflow = clone(flow.subflows[subflowId]);
            var nodeIds = Object.keys(subflow.nodes);
            subflow.nodes = nodeIds.map(function(id) {
                return subflow.nodes[id];
            });
            if (subflow.configs) {
                var configIds = Object.keys(subflow.configs);
                subflow.configs = configIds.map(function(id) {
                    return subflow.configs[id];
                })
            }
            delete subflow.instances;
            return subflow;
        });
        if (result.subflows.length === 0) {
            delete result.subflows;
        }
    }
    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.getFlows"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>getFlows ()](#apidoc.element.node-red.nodes.getFlows)
- description and source-code
```javascript
function getFlows() {
    return activeConfig;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.getModuleInfo"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>getModuleInfo (module)](#apidoc.element.node-red.nodes.getModuleInfo)
- description and source-code
```javascript
function getModuleInfo(module) {
    if (moduleNodes[module]) {
        var nodes = moduleNodes[module];
        var m = {
            name: module,
            version: moduleConfigs[module].version,
            local: moduleConfigs[module].local,
            nodes: []
        };
        for (var i = 0; i < nodes.length; ++i) {
            var nodeInfo = filterNodeInfo(moduleConfigs[module].nodes[nodes[i]]);
            nodeInfo.version = m.version;
            m.nodes.push(nodeInfo);
        }
        return m;
    } else {
        return null;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.getNode"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>getNode (id)](#apidoc.element.node-red.nodes.getNode)
- description and source-code
```javascript
function getNode(id) {
    var node;
    if (activeNodesToFlow[id] && activeFlows[activeNodesToFlow[id]]) {
        return activeFlows[activeNodesToFlow[id]].getNode(id);
    }
    for (var flowId in activeFlows) {
        if (activeFlows.hasOwnProperty(flowId)) {
            node = activeFlows[flowId].getNode(id);
            if (node) {
                return node;
            }
        }
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.getNodeConfig"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>getNodeConfig (id, lang)](#apidoc.element.node-red.nodes.getNodeConfig)
- description and source-code
```javascript
function getNodeConfig(id, lang) {
    var config = moduleConfigs[getModule(id)];
    if (!config) {
        return null;
    }
    config = config.nodes[getNode(id)];
    if (config) {
        var result = config.config;
        result += loader.getNodeHelp(config,lang||"en-US")

        //if (config.script) {
        //    result += '<script type="text/javascript">'+config.script+'</script>';
        //}
        return result;
    } else {
        return null;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.getNodeConfigs"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>getNodeConfigs (lang)](#apidoc.element.node-red.nodes.getNodeConfigs)
- description and source-code
```javascript
function getAllNodeConfigs(lang) {
    if (!nodeConfigCache) {
        var result = "";
        var script = "";
        for (var i=0;i<nodeList.length;i++) {
            var id = nodeList[i];
            var config = moduleConfigs[getModule(id)].nodes[getNode(id)];
            if (config.enabled && !config.err) {
                result += config.config;
                result += loader.getNodeHelp(config,lang||"en-US")||"";
                //script += config.script;
            }
        }
        //if (script.length > 0) {
        //    result += '<script type="text/javascript">';
        //    result += UglifyJS.minify(script, {fromString: true}).code;
        //    result += '</script>';
        //}
        nodeConfigCache = result;
    }
    return nodeConfigCache;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.getNodeInfo"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>getNodeInfo (typeOrId)](#apidoc.element.node-red.nodes.getNodeInfo)
- description and source-code
```javascript
function getNodeInfo(typeOrId) {
    var id = typeOrId;
    if (nodeTypeToId.hasOwnProperty(typeOrId)) {
        id = nodeTypeToId[typeOrId];
    }
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (id) {
        var module = moduleConfigs[getModule(id)];
        if (module) {
            var config = module.nodes[getNode(id)];
            if (config) {
                var info = filterNodeInfo(config);
                if (config.hasOwnProperty("loaded")) {
                    info.loaded = config.loaded;
                }
                info.version = module.version;
                return info;
            }
        }
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.getNodeList"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>getNodeList (filter)](#apidoc.element.node-red.nodes.getNodeList)
- description and source-code
```javascript
function getNodeList(filter) {
    var list = [];
    for (var module in moduleConfigs) {
<span class="apidocCodeCommentSpan">        /* istanbul ignore else */
</span>        if (moduleConfigs.hasOwnProperty(module)) {
            var nodes = moduleConfigs[module].nodes;
            for (var node in nodes) {
                /* istanbul ignore else */
                if (nodes.hasOwnProperty(node)) {
                    var nodeInfo = filterNodeInfo(nodes[node]);
                    nodeInfo.version = moduleConfigs[module].version;
                    if (!filter || filter(nodes[node])) {
                        list.push(nodeInfo);
                    }
                }
            }
        }
    }
    return list;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.getType"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>getType (type)](#apidoc.element.node-red.nodes.getType)
- description and source-code
```javascript
function getNodeConstructor(type) {
    var id = nodeTypeToId[type];

    var config;
    if (typeof id === "undefined") {
        config = undefined;
    } else {
        config = moduleConfigs[getModule(id)].nodes[getNode(id)];
    }

    if (!config || (config.enabled && !config.err)) {
        return nodeConstructors[type];
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.init"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>init (runtime)](#apidoc.element.node-red.nodes.init)
- description and source-code
```javascript
function init(runtime) {
    settings = runtime.settings;
    credentials.init(runtime);
    flows.init(runtime);
    registry.init(runtime);
    context.init(runtime.settings);
}
```
- example usage
```shell
...
settings.flowFile = flowFile;
}
if (parsedArgs.userDir) {
settings.userDir = parsedArgs.userDir;
}

try {
RED.init(server,settings);
} catch(err) {
if (err.code == "unsupported_version") {
    console.log("Unsupported version of node.js:",process.version);
    console.log("Node-RED requires node.js v4 or later");
} else if  (err.code == "not_built") {
    console.log("Node-RED has not been built. See README.md for details");
} else {
...
```

#### <a name="apidoc.element.node-red.nodes.installModule"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>installModule (module)](#apidoc.element.node-red.nodes.installModule)
- description and source-code
```javascript
function installModule(module) {
    //TODO: ensure module is 'safe'
    return when.promise(function(resolve,reject) {
        var installName = module;

        try {
            if (moduleRe.test(module)) {
                // Simple module name - assume it can be npm installed
            } else if (slashRe.test(module)) {
                // A path - check if there's a valid package.json
                installName = module;
                module = checkModulePath(module);
            }
            checkExistingModule(module);
        } catch(err) {
            return reject(err);
        }
        log.info(log._("server.install.installing",{name: module}));

        var installDir = settings.userDir || process.env.NODE_RED_HOME || ".";
        var child = child_process.execFile(npmCommand,['install','--production',installName],
            {
                cwd: installDir
            },
            function(err, stdin, stdout) {
                if (err) {
                    var lookFor404 = new RegExp(" 404 .*"+installName+"$","m");
                    if (lookFor404.test(stdout)) {
                        log.warn(log._("server.install.install-failed-not-found",{name:module}));
                        var e = new Error("Module not found");
                        e.code = 404;
                        reject(e);
                    } else {
                        log.warn(log._("server.install.install-failed-long",{name:module}));
                        log.warn("------------------------------------------");
                        log.warn(err.toString());
                        log.warn("------------------------------------------");
                        reject(new Error(log._("server.install.install-failed")));
                    }
                } else {
                    log.info(log._("server.install.installed",{name:module}));
                    resolve(require("./index").addModule(module).then(reportAddedModules));
                }
            }
        );
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.load"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>load ()](#apidoc.element.node-red.nodes.load)
- description and source-code
```javascript
function load() {
    registry.load();
    return installer.checkPrereq().then(loader.load);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.loadFlows"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>loadFlows ()](#apidoc.element.node-red.nodes.loadFlows)
- description and source-code
```javascript
function load() {
    return setFlows(null,"load",false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.paletteEditorEnabled"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>paletteEditorEnabled ()](#apidoc.element.node-red.nodes.paletteEditorEnabled)
- description and source-code
```javascript
paletteEditorEnabled = function () {
    return paletteEditorEnabled
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.registerType"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>registerType (nodeSet, type, constructor, opts)](#apidoc.element.node-red.nodes.registerType)
- description and source-code
```javascript
function registerType(nodeSet, type, constructor, opts) {
    if (typeof type !== "string") {
        // This is someone calling the api directly, rather than via the
        // RED object provided to a node. Log a warning
        log.warn("["+nodeSet+"] Deprecated call to RED.runtime.nodes.registerType - node-set name must be provided as first argument
");
        opts = constructor;
        constructor = type;
        type = nodeSet;
        nodeSet = "";
    }
    if (opts && opts.credentials) {
        credentials.register(type,opts.credentials);
    }
    registry.registerType(nodeSet,type,constructor);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.removeFlow"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>removeFlow (id)](#apidoc.element.node-red.nodes.removeFlow)
- description and source-code
```javascript
function removeFlow(id) {
    if (id === 'global') {
        // TODO: nls + error code
        throw new Error('not allowed to remove global');
    }
    var flow = activeFlowConfig.flows[id];
    if (!flow) {
        var e = new Error();
        e.code = 404;
        throw e;
    }

    var newConfig = clone(activeConfig.flows);
    newConfig = newConfig.filter(function(node) {
        return node.z !== id && node.id !== id;
    });

    return setFlows(newConfig,'flows',true).then(function() {
        log.info(log._("nodes.flows.removed-flow",{label:(flow.label?flow.label+" ":"")+"["+flow.id+"]"}));
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.setFlows"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>setFlows (_config, type, muteLog)](#apidoc.element.node-red.nodes.setFlows)
- description and source-code
```javascript
function setFlows(_config, type, muteLog) {
    type = type||"full";

    var configSavePromise = null;
    var config = null;
    var diff;
    var newFlowConfig;
    var isLoad = false;
    if (type === "load") {
        isLoad = true;
        configSavePromise = loadFlows().then(function(_config) {
            config = clone(_config.flows);
            newFlowConfig = flowUtil.parseConfig(clone(config));
            type = "full";
            return _config.rev;
        });
    } else {
        config = clone(_config);
        newFlowConfig = flowUtil.parseConfig(clone(config));
        if (type !== 'full') {
            diff = flowUtil.diffConfigs(activeFlowConfig,newFlowConfig);
        }
        credentials.clean(config);
        var credsDirty = credentials.dirty();
        configSavePromise = credentials.export().then(function(creds) {
            var saveConfig = {
                flows: config,
                credentialsDirty:credsDirty,
                credentials: creds
            }
            return storage.saveFlows(saveConfig);
        });
    }

    return configSavePromise
        .then(function(flowRevision) {
            if (!isLoad) {
                log.debug("saved flow revision: "+flowRevision);
            }
            activeConfig = {
                flows:config,
                rev:flowRevision
            };
            activeFlowConfig = newFlowConfig;
            if (started) {
                return stop(type,diff,muteLog).then(function() {
                    context.clean(activeFlowConfig);
                    start(type,diff,muteLog);
                    return flowRevision;
                }).otherwise(function(err) {
                })
            }
        });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.startFlows"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>startFlows (type, diff, muteLog)](#apidoc.element.node-red.nodes.startFlows)
- description and source-code
```javascript
function start(type, diff, muteLog) {
    //dumpActiveNodes();
    type = type||"full";
    started = true;
    var i;
    if (activeFlowConfig.missingTypes.length > 0) {
        log.info(log._("nodes.flows.missing-types"));
        var knownUnknowns = 0;
        for (i=0;i<activeFlowConfig.missingTypes.length;i++) {
            var nodeType = activeFlowConfig.missingTypes[i];
            var info = deprecated.get(nodeType);
            if (info) {
                log.info(log._("nodes.flows.missing-type-provided",{type:activeFlowConfig.missingTypes[i],module:info.module}));
                knownUnknowns += 1;
            } else {
                log.info(" - "+activeFlowConfig.missingTypes[i]);
            }
        }
        if (knownUnknowns > 0) {
            log.info(log._("nodes.flows.missing-type-install-1"));
            log.info("  npm install <module name>");
            log.info(log._("nodes.flows.missing-type-install-2"));
            log.info("  "+settings.userDir);
        }
        events.emit("runtime-event",{id:"runtime-state",type:"warning",text:"notification.warnings.missing-types"});
        return when.resolve();
    }
    if (!muteLog) {
        if (diff) {
            log.info(log._("nodes.flows.starting-modified-"+type));
        } else {
            log.info(log._("nodes.flows.starting-flows"));
        }
    }
    var id;
    if (!diff) {
        if (!activeFlows['global']) {
            activeFlows['global'] = Flow.create(activeFlowConfig);
        }
        for (id in activeFlowConfig.flows) {
            if (activeFlowConfig.flows.hasOwnProperty(id)) {
                if (!activeFlows[id]) {
                    activeFlows[id] = Flow.create(activeFlowConfig,activeFlowConfig.flows[id]);
                }
            }
        }
    } else {
        activeFlows['global'].update(activeFlowConfig,activeFlowConfig);
        for (id in activeFlowConfig.flows) {
            if (activeFlowConfig.flows.hasOwnProperty(id)) {
                if (activeFlows[id]) {
                    activeFlows[id].update(activeFlowConfig,activeFlowConfig.flows[id]);
                } else {
                    activeFlows[id] = Flow.create(activeFlowConfig,activeFlowConfig.flows[id]);
                }
            }
        }
    }

    for (id in activeFlows) {
        if (activeFlows.hasOwnProperty(id)) {
            activeFlows[id].start(diff);
            var activeNodes = activeFlows[id].getActiveNodes();
            Object.keys(activeNodes).forEach(function(nid) {
                activeNodesToFlow[nid] = id;
                if (activeNodes[nid]._alias) {
                    subflowInstanceNodeMap[activeNodes[nid]._alias] = subflowInstanceNodeMap[activeNodes[nid]._alias] || [];
                    subflowInstanceNodeMap[activeNodes[nid]._alias].push(nid);
                }
            });

        }
    }
    events.emit("nodes-started");
    events.emit("runtime-event",{id:"runtime-state"});

    if (!muteLog) {
        if (diff) {
            log.info(log._("nodes.flows.started-modified-"+type));
        } else {
            log.info(log._("nodes.flows.started-flows"));
        }
    }
    return when.resolve();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.stopFlows"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>stopFlows (type, diff, muteLog)](#apidoc.element.node-red.nodes.stopFlows)
- description and source-code
```javascript
function stop(type, diff, muteLog) {
    type = type||"full";
    if (!muteLog) {
        if (diff) {
            log.info(log._("nodes.flows.stopping-modified-"+type));
        } else {
            log.info(log._("nodes.flows.stopping-flows"));
        }
    }
    started = false;
    var promises = [];
    var stopList;
    if (type === 'nodes') {
        stopList = diff.changed.concat(diff.removed);
    } else if (type === 'flows') {
        stopList = diff.changed.concat(diff.removed).concat(diff.linked);
    }
    for (var id in activeFlows) {
        if (activeFlows.hasOwnProperty(id)) {
            promises = promises.concat(activeFlows[id].stop(stopList));
            if (!diff || diff.removed.indexOf(id)!==-1) {
                delete activeFlows[id];
            }
        }
    }

    return when.promise(function(resolve,reject) {
        when.settle(promises).then(function() {
            for (id in activeNodesToFlow) {
                if (activeNodesToFlow.hasOwnProperty(id)) {
                    if (!activeFlows[activeNodesToFlow[id]]) {
                        delete activeNodesToFlow[id];
                    }
                }
            }
            if (stopList) {
                stopList.forEach(function(id) {
                    delete activeNodesToFlow[id];
                });
            }
            // Ideally we'd prune just what got stopped - but mapping stopList
            // id to the list of subflow instance nodes is something only Flow
            // can do... so cheat by wiping the map knowing it'll be rebuilt
            // in start()
            subflowInstanceNodeMap = {};
            if (!muteLog) {
                if (diff) {
                    log.info(log._("nodes.flows.stopped-modified-"+type));
                } else {
                    log.info(log._("nodes.flows.stopped-flows"));
                }
            }
            resolve();
        });
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.uninstallModule"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>uninstallModule (module)](#apidoc.element.node-red.nodes.uninstallModule)
- description and source-code
```javascript
function uninstallModule(module) {
    var info = registry.getModuleInfo(module);
    if (!info) {
        throw new Error(log._("nodes.index.unrecognised-module", {module:module}));
    } else {
        for (var i=0;i<info.nodes.length;i++) {
            flows.checkTypeInUse(module+"/"+info.nodes[i].name);
        }
        return registry.uninstallModule(module);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.nodes.updateFlow"></a>[function <span class="apidocSignatureSpan">node-red.nodes.</span>updateFlow (id, newFlow)](#apidoc.element.node-red.nodes.updateFlow)
- description and source-code
```javascript
function updateFlow(id, newFlow) {
    var label = id;
    if (id !== 'global') {
        if (!activeFlowConfig.flows[id]) {
            var e = new Error();
            e.code = 404;
            throw e;
        }
        label = activeFlowConfig.flows[id].label;
    }
    var newConfig = clone(activeConfig.flows);
    var nodes;

    if (id === 'global') {
        // Remove all nodes whose z is not a known flow
        // When subflows can be owned by a flow, this logic will have to take
        // that into account
        newConfig = newConfig.filter(function(node) {
            return node.type === 'tab' || (node.hasOwnProperty('z') && activeFlowConfig.flows.hasOwnProperty(node.z));
        })

        // Add in the new config nodes
        nodes = newFlow.configs||[];
        if (newFlow.subflows) {
            // Add in the new subflows
            newFlow.subflows.forEach(function(sf) {
                nodes = nodes.concat(sf.nodes||[]).concat(sf.configs||[]);
                delete sf.nodes;
                delete sf.configs;
                nodes.push(sf);
            });
        }
    } else {
        newConfig = newConfig.filter(function(node) {
            return node.z !== id && node.id !== id;
        });
        var tabNode = {
            type:'tab',
            label:newFlow.label,
            id:id
        }
        nodes = [tabNode].concat(newFlow.nodes||[]).concat(newFlow.configs||[]);
        nodes.forEach(function(n) {
            n.z = id;
        });
    }

    newConfig = newConfig.concat(nodes);
    return setFlows(newConfig,'flows',true).then(function() {
        log.info(log._("nodes.flows.updated-flow",{label:(label?label+" ":"")+"["+id+"]"}));
    })
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-red.settings"></a>[module node-red.settings](#apidoc.module.node-red.settings)

#### <a name="apidoc.element.node-red.settings.available"></a>[function <span class="apidocSignatureSpan">node-red.settings.</span>available ()](#apidoc.element.node-red.settings.available)
- description and source-code
```javascript
available = function () {
    return (globalSettings !== null);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.settings.delete"></a>[function <span class="apidocSignatureSpan">node-red.settings.</span>delete (prop)](#apidoc.element.node-red.settings.delete)
- description and source-code
```javascript
delete = function (prop) {
    if (userSettings.hasOwnProperty(prop)) {
        throw new Error(log._("settings.property-read-only", {prop:prop}));
    }
    if (globalSettings === null) {
        throw new Error(log._("settings.not-available"));
    }
    if (globalSettings.hasOwnProperty(prop)) {
        delete globalSettings[prop];
        return storage.saveSettings(globalSettings);
    }
    return when.resolve();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.settings.get"></a>[function <span class="apidocSignatureSpan">node-red.settings.</span>get (prop)](#apidoc.element.node-red.settings.get)
- description and source-code
```javascript
get = function (prop) {
    if (userSettings.hasOwnProperty(prop)) {
        return clone(userSettings[prop]);
    }
    if (globalSettings === null) {
        throw new Error(log._("settings.not-available"));
    }
    return clone(globalSettings[prop]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.settings.init"></a>[function <span class="apidocSignatureSpan">node-red.settings.</span>init (settings)](#apidoc.element.node-red.settings.init)
- description and source-code
```javascript
init = function (settings) {
    userSettings = settings;
    for (var i in settings) {
<span class="apidocCodeCommentSpan">        /* istanbul ignore else */
</span>        if (settings.hasOwnProperty(i) && i !== 'load' && i !== 'get' && i !== 'set' && i !== 'available' && i !== 'reset') {
            // Don't allow any of the core functions get replaced via settings
            (function() {
                var j = i;
                persistentSettings.__defineGetter__(j,function() { return userSettings[j]; });
                persistentSettings.__defineSetter__(j,function() { throw new Error("Property '"+j+"' is read-only"); });
            })();
        }
    }
    globalSettings = null;
}
```
- example usage
```shell
...
settings.flowFile = flowFile;
}
if (parsedArgs.userDir) {
settings.userDir = parsedArgs.userDir;
}

try {
RED.init(server,settings);
} catch(err) {
if (err.code == "unsupported_version") {
    console.log("Unsupported version of node.js:",process.version);
    console.log("Node-RED requires node.js v4 or later");
} else if  (err.code == "not_built") {
    console.log("Node-RED has not been built. See README.md for details");
} else {
...
```

#### <a name="apidoc.element.node-red.settings.load"></a>[function <span class="apidocSignatureSpan">node-red.settings.</span>load (_storage)](#apidoc.element.node-red.settings.load)
- description and source-code
```javascript
load = function (_storage) {
    storage = _storage;
    return storage.getSettings().then(function(_settings) {
        globalSettings = _settings;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.settings.reset"></a>[function <span class="apidocSignatureSpan">node-red.settings.</span>reset ()](#apidoc.element.node-red.settings.reset)
- description and source-code
```javascript
reset = function () {
    for (var i in userSettings) {
<span class="apidocCodeCommentSpan">        /* istanbul ignore else */
</span>        if (userSettings.hasOwnProperty(i)) {
            delete persistentSettings[i];
        }
    }
    userSettings = null;
    globalSettings = null;
    storage = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.settings.set"></a>[function <span class="apidocSignatureSpan">node-red.settings.</span>set (prop, value)](#apidoc.element.node-red.settings.set)
- description and source-code
```javascript
set = function (prop, value) {
    if (userSettings.hasOwnProperty(prop)) {
        throw new Error(log._("settings.property-read-only", {prop:prop}));
    }
    if (globalSettings === null) {
        throw new Error(log._("settings.not-available"));
    }
    var current = globalSettings[prop];
    globalSettings[prop] = value;
    try {
        assert.deepEqual(current,value);
        return when.resolve();
    } catch(err) {
        return storage.saveSettings(globalSettings);
    }
}
```
- example usage
```shell
...

    return function(req,res,next) {
        if (req.method === 'OPTIONS') {
            return next();
        }
        var requestUser = basicAuth(req);
        if (!requestUser || requestUser.name !== user || !checkPassword(requestUser.pass)) {
            res.set('WWW-Authenticate', 'Basic realm=Authorization Required');
            return res.sendStatus(401);
        }
        next();
    }
}

if (settings.httpAdminRoot !== false && settings.httpAdminAuth) {
...
```



# <a name="apidoc.module.node-red.settings.functionGlobalContext"></a>[module node-red.settings.functionGlobalContext](#apidoc.module.node-red.settings.functionGlobalContext)

#### <a name="apidoc.element.node-red.settings.functionGlobalContext.get"></a>[function <span class="apidocSignatureSpan">node-red.settings.functionGlobalContext.</span>get (key)](#apidoc.element.node-red.settings.functionGlobalContext.get)
- description and source-code
```javascript
function get(key) {
    return util.getMessageProperty(data,key);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.settings.functionGlobalContext.set"></a>[function <span class="apidocSignatureSpan">node-red.settings.functionGlobalContext.</span>set (key, value)](#apidoc.element.node-red.settings.functionGlobalContext.set)
- description and source-code
```javascript
function set(key, value) {
    util.setMessageProperty(data,key,value);
}
```
- example usage
```shell
...

    return function(req,res,next) {
        if (req.method === 'OPTIONS') {
            return next();
        }
        var requestUser = basicAuth(req);
        if (!requestUser || requestUser.name !== user || !checkPassword(requestUser.pass)) {
            res.set('WWW-Authenticate', 'Basic realm=Authorization Required');
            return res.sendStatus(401);
        }
        next();
    }
}

if (settings.httpAdminRoot !== false && settings.httpAdminAuth) {
...
```



# <a name="apidoc.module.node-red.util"></a>[module node-red.util](#apidoc.module.node-red.util)

#### <a name="apidoc.element.node-red.util.cloneMessage"></a>[function <span class="apidocSignatureSpan">node-red.util.</span>cloneMessage (msg)](#apidoc.element.node-red.util.cloneMessage)
- description and source-code
```javascript
function cloneMessage(msg) {
    // Temporary fix for #97
    // TODO: remove this http-node-specific fix somehow
    var req = msg.req;
    var res = msg.res;
    delete msg.req;
    delete msg.res;
    var m = clone(msg);
    if (req) {
        m.req = req;
        msg.req = req;
    }
    if (res) {
        m.res = res;
        msg.res = res;
    }
    return m;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.util.compareObjects"></a>[function <span class="apidocSignatureSpan">node-red.util.</span>compareObjects (obj1, obj2)](#apidoc.element.node-red.util.compareObjects)
- description and source-code
```javascript
function compareObjects(obj1, obj2) {
    var i;
    if (obj1 === obj2) {
        return true;
    }
    if (obj1 == null || obj2 == null) {
        return false;
    }

    var isArray1 = Array.isArray(obj1);
    var isArray2 = Array.isArray(obj2);
    if (isArray1 != isArray2) {
        return false;
    }
    if (isArray1 && isArray2) {
        if (obj1.length !== obj2.length) {
            return false;
        }
        for (i=0;i<obj1.length;i++) {
            if (!compareObjects(obj1[i],obj2[i])) {
                return false;
            }
        }
        return true;
    }
    var isBuffer1 = Buffer.isBuffer(obj1);
    var isBuffer2 = Buffer.isBuffer(obj2);
    if (isBuffer1 != isBuffer2) {
        return false;
    }
    if (isBuffer1 && isBuffer2) {
        if (obj1.equals) {
            // For node 0.12+ - use the native equals
            return obj1.equals(obj2);
        } else {
            if (obj1.length !== obj2.length) {
                return false;
            }
            for (i=0;i<obj1.length;i++) {
                if (obj1.readUInt8(i) !== obj2.readUInt8(i)) {
                    return false;
                }
            }
            return true;
        }
    }

    if (typeof obj1 !== 'object' || typeof obj2 !== 'object') {
        return false;
    }
    var keys1 = Object.keys(obj1);
    var keys2 = Object.keys(obj2);
    if (keys1.length != keys2.length) {
        return false;
    }
    for (var k in obj1) {
<span class="apidocCodeCommentSpan">        /* istanbul ignore else */
</span>        if (obj1.hasOwnProperty(k)) {
            if (!compareObjects(obj1[k],obj2[k])) {
                return false;
            }
        }
    }
    return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.util.ensureBuffer"></a>[function <span class="apidocSignatureSpan">node-red.util.</span>ensureBuffer (o)](#apidoc.element.node-red.util.ensureBuffer)
- description and source-code
```javascript
function ensureBuffer(o) {
    if (Buffer.isBuffer(o)) {
        return o;
    } else if (typeof o === "object") {
        o = JSON.stringify(o);
    } else if (typeof o !== "string") {
        o = ""+o;
    }
    return new Buffer(o);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.util.ensureString"></a>[function <span class="apidocSignatureSpan">node-red.util.</span>ensureString (o)](#apidoc.element.node-red.util.ensureString)
- description and source-code
```javascript
function ensureString(o) {
    if (Buffer.isBuffer(o)) {
        return o.toString();
    } else if (typeof o === "object") {
        return JSON.stringify(o);
    } else if (typeof o === "string") {
        return o;
    }
    return ""+o;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.util.evaluateNodeProperty"></a>[function <span class="apidocSignatureSpan">node-red.util.</span>evaluateNodeProperty (value, type, node, msg)](#apidoc.element.node-red.util.evaluateNodeProperty)
- description and source-code
```javascript
function evaluateNodeProperty(value, type, node, msg) {
    if (type === 'str') {
        return ""+value;
    } else if (type === 'num') {
        return Number(value);
    } else if (type === 'json') {
        return JSON.parse(value);
    } else if (type === 're') {
        return new RegExp(value);
    } else if (type === 'date') {
        return Date.now();
    } else if (type === 'msg' && msg) {
        return getMessageProperty(msg,value);
    } else if (type === 'flow' && node) {
        return node.context().flow.get(value);
    } else if (type === 'global' && node) {
        return node.context().global.get(value);
    } else if (type === 'bool') {
        return /^true$/i.test(value);
    } else if (type === 'jsonata') {
        return jsonata(value).evaluate({msg:msg});
    }
    return value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.util.generateId"></a>[function <span class="apidocSignatureSpan">node-red.util.</span>generateId ()](#apidoc.element.node-red.util.generateId)
- description and source-code
```javascript
function generateId() {
    return (1+Math.random()*4294967295).toString(16);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.util.getMessageProperty"></a>[function <span class="apidocSignatureSpan">node-red.util.</span>getMessageProperty (msg, expr)](#apidoc.element.node-red.util.getMessageProperty)
- description and source-code
```javascript
function getMessageProperty(msg, expr) {
    var result = null;
    if (expr.indexOf('msg.')===0) {
        expr = expr.substring(4);
    }
    var msgPropParts = normalisePropertyExpression(expr);
    var m;
    msgPropParts.reduce(function(obj, key) {
        result = (typeof obj[key] !== "undefined" ? obj[key] : undefined);
        return result;
    }, msg);
    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.util.normalisePropertyExpression"></a>[function <span class="apidocSignatureSpan">node-red.util.</span>normalisePropertyExpression (str)](#apidoc.element.node-red.util.normalisePropertyExpression)
- description and source-code
```javascript
function normalisePropertyExpression(str) {
    // This must be kept in sync with validatePropertyExpression
    // in editor/js/ui/utils.js

    var length = str.length;
    if (length === 0) {
        throw new Error("Invalid property expression: zero-length");
    }
    var parts = [];
    var start = 0;
    var inString = false;
    var inBox = false;
    var quoteChar;
    var v;
    for (var i=0;i<length;i++) {
        var c = str[i];
        if (!inString) {
            if (c === "'" || c === '"') {
                if (i != start) {
                    throw new Error("Invalid property expression: unexpected "+c+" at position "+i);
                }
                inString = true;
                quoteChar = c;
                start = i+1;
            } else if (c === '.') {
                if (i===0) {
                    throw new Error("Invalid property expression: unexpected . at position 0");
                }
                if (start != i) {
                    v = str.substring(start,i);
                    if (/^\d+$/.test(v)) {
                        parts.push(parseInt(v));
                    } else {
                        parts.push(v);
                    }
                }
                if (i===length-1) {
                    throw new Error("Invalid property expression: unterminated expression");
                }
                // Next char is first char of an identifier: a-z 0-9 $ _
                if (!/[a-z0-9\$\_]/i.test(str[i+1])) {
                    throw new Error("Invalid property expression: unexpected "+str[i+1]+" at position "+(i+1));
                }
                start = i+1;
            } else if (c === '[') {
                if (i === 0) {
                    throw new Error("Invalid property expression: unexpected "+c+" at position "+i);
                }
                if (start != i) {
                    parts.push(str.substring(start,i));
                }
                if (i===length-1) {
                    throw new Error("Invalid property expression: unterminated expression");
                }
                // Next char is either a quote or a number
                if (!/["'\d]/.test(str[i+1])) {
                    throw new Error("Invalid property expression: unexpected "+str[i+1]+" at position "+(i+1));
                }
                start = i+1;
                inBox = true;
            } else if (c === ']') {
                if (!inBox) {
                    throw new Error("Invalid property expression: unexpected "+c+" at position "+i);
                }
                if (start != i) {
                    v = str.substring(start,i);
                    if (/^\d+$/.test(v)) {
                        parts.push(parseInt(v));
                    } else {
                        throw new Error("Invalid property expression: unexpected array expression at position "+start);
                    }
                }
                start = i+1;
                inBox = false;
            } else if (c === ' ') {
                throw new Error("Invalid property expression: unexpected ' ' at position "+i);
            }
        } else {
            if (c === quoteChar) {
                if (i-start === 0) {
                    throw new Error("Invalid property expression: zero-length string at position "+start);
                }
                parts.push(str.substring(start,i));
                // If inBox, next char must be a ]. Otherwise it may be [ or .
                if (inBox && !/\]/.test(str[i+1])) {
                    throw new Error("Invalid property expression: unexpected array expression at position "+start);
                } else if (!inBox && i+1!==length && !/[\[\.]/.test(str[i+1])) {
                    throw new Error("Invalid property expression: unexpected "+str[i+1]+" expression at position "+(i+1));
                }
                start = i+1;
                inString = false;
            }
        }

    }
    if (inBox || inString) {
        throw new Error("Invalid property expression: unterminated expression");
    }
    if ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-red.util.setMessageProperty"></a>[function <span class="apidocSignatureSpan">node-red.util.</span>setMessageProperty (msg, prop, value, createMissing)](#apidoc.element.node-red.util.setMessageProperty)
- description and source-code
```javascript
function setMessageProperty(msg, prop, value, createMissing) {
    if (typeof createMissing === 'undefined') {
        createMissing = (typeof value !== 'undefined');
    }
    if (prop.indexOf('msg.')===0) {
        prop = prop.substring(4);
    }
    var msgPropParts = normalisePropertyExpression(prop);
    var depth = 0;
    var length = msgPropParts.length;
    var obj = msg;
    var key;
    for (var i=0;i<length-1;i++) {
        key = msgPropParts[i];
        if (typeof key === 'string' || (typeof key === 'number' && !Array.isArray(obj))) {
            if (obj.hasOwnProperty(key)) {
                obj = obj[key];
            } else if (createMissing) {
                if (typeof msgPropParts[i+1] === 'string') {
                    obj[key] = {};
                } else {
                    obj[key] = [];
                }
                obj = obj[key];
            } else {
                return null;
            }
        } else if (typeof key === 'number') {
            // obj is an array
            if (obj[key] === undefined) {
                if (createMissing) {
                    if (typeof msgPropParts[i+1] === 'string') {
                        obj[key] = {};
                    } else {
                        obj[key] = [];
                    }
                    obj = obj[key];
                } else {
                    return null
                }
            } else {
                obj = obj[key];
            }
        }
    }
    key = msgPropParts[length-1];
    if (typeof value === "undefined") {
        if (typeof key === 'number' && Array.isArray(obj)) {
            obj.splice(key,1);
        } else {
            delete obj[key]
        }
    } else {
        obj[key] = value;
    }
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
