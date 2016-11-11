## HOCON

    akka {
        # here we are configuring log levels
        loggers = ["Akka.Logger.Serilog.SerilogLogger, Akka.Logger.Serilog"]
        log-config-on-start = off
        stdout-loglevel = INFO
        loglevel = ERROR
        # this config section will be referenced as akka.actor
        actor {
            provider = "Akka.Remote.RemoteActorRefProvider, Akka.Remote"
            debug {
                receive = on
            }
        }
    }
