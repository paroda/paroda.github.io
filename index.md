# List of projects

## Live debugging clojure web applications hosted on Azure App Services

[paroda/az-ws-debug](https://GitHub.com/paroda/az-ws-debug)

Clojure can be used to build web applications that can be deployed on Microsoft Azure Websites. Developing the application locally is a great deal of fun with the awesome REPL. The repl is also a highly effective mean to observe the live process and troubleshoot tricky issues. However, once it is deployed to Azure, there is no longer an easy way to access a REPL to the live application. This is a small helper to gain that REPL access again. It is quite simple, but highly effective at troubleshooting the live application even in the production environment without any performance hit.

**It doesn't require any kind of addition or modification to your existing clojure web application.**

A simple REPL can be started on a Clojure application just by one simple java option `-Dclojure.server.repl="{:port 9000 :accept clojure.core.server/repl}"`. With this, Clojure would automatically start a *Socket REPL* on port *9000*. The trick is to make this REPL accessible somehow on your local machine. That is the purpose of this tool.

See [paroda/az-ws-debug](https://GitHub.com/paroda/az-ws-debug) to get this tool and how to use it.

