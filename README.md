# Certificate Plugin for Apache Cordova

For Android only. Modified hyper2k's code

cordova Plugin to configure SSL Certificates, currently used to enable usage of untrusted  aka self-signed SSL certifcates
 
[![NPM](https://nodei.co/npm/cordova-plugin-certificates.png)](https://nodei.co/npm/cordova-plugin-certificates/)


## Documentation

### Install

```
cordova plugin add cordova-plugin-certificates
```
### Usage

Activate insecure certificates
```
cordova.plugins.certificates.trustUnsecureCerts(true)
```

Dectivate insecure certificates
```
cordova.plugins.certificates.trustUnsecureCerts(false)
```

