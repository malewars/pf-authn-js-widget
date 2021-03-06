# Guide for Using Risk-Based Authentication With the Widget

Extra steps may be required to set up the widget when using adapters with risk-based authentication ability.

**Table of Contents**
- [ID DataWeb Integration Kit](#id-dataweb-integration-kit)

## ID DataWeb Integration Kit

### Dependencies requirement

* ID DataWeb Integration Kit 1.1 or later

### Setup

If you have configured the adapter so that the `Device Profiling Method` is set to `Captured by this adapter`, no extra setup is required as the widget will be able to run the device profiling script with information provided by the adapter. However if you have chosen `Captured by a previous adapter` you will need to place the device profiling script that came with the kit (`id_dataweb_device_profiling.js`) to where your application will be hosted and attach the following script in the index.html that you have created. 
```html
<script language="javascript" src="id_dataweb_device_profiling.js"></script>
```