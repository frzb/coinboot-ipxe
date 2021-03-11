# iPXE Remote Logging for Coinboot

This is a customised fork of iPXE for Coinboot.  
They only change is that remote syslog logging is activated.

This is done via these changes at `src/config/console.h`:

## Enable syslog console output

```
#define        CONSOLE_SYSLOG          /* Syslog console */
```


## Enable log messages in syslog console output

```
#define        LOG_LEVEL       LOG_ALL
```

# Further readings

For more details about iPXE console usage please refer to: http://ipxe.org/console#console_usages
