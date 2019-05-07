# ![LOGO](logo.png) Wayback MSP Connector

## Description

A generated MSP connector for the Wayback API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/archive.org/wayback/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T11:17:13+03:00

## API Description

API for Internet Archive's Wayback Machine

## Authorization

This API does not require authorization.

## Actions

### get_wayback_v1_available

#### Input Parameters
* `url` - _required_ - A single URL to query.
* `timestamp` - _optional_ - Timestamp requested in ISO 8601 format. The following formats are acceptable:
 - YYYY
 - YYYY-MM
 - YYYY-MM-DD
 - YYYY-MM-DDTHH:mm:SSz
 - YYYY-MM-DD:HH:mm+00:00

* `callback` - _optional_ - Specifies a JavaScript function func, for a JSON-P response. When provided, results are wrapped as `callback(data)`, and the returned MIME type is application/javascript. This causes the caller to automatically run the func with the JSON results as its argument.

* `timeout` - _optional_ - Timeout is the maximum number of seconds to wait for the availability API to get its underlying results from the CDX server. The default value is 5.0.

* `closest` - _optional_ - The direction specifies whether to match archived timestamps that are before the provided one, after, or the default either (closest in either direction). Must be before, after, or either. May be overidden by individual requests.

    Possible values: either, before, after.
* `status_code` - _optional_ - HTTP status codes to filter by. Only results with these codes will be returned

    Possible values: 200, 201, 202, 203, 204, 205, 206, 300, 301, 302, 303, 304, 305, 306, 307, 308, 400, 401, 402, 403, 404, 405, 406, 407, 408, 409, 410, 411, 412, 413, 414, 415, 416, 417, 418, 421, 426, 428, 429, 431, 500, 501, 502, 503, 504, 505, 506, 507, 511.
* `tag` - _optional_ - The optional tag can have any value, and is returned with the results; it can be used to help collate input and output values.


### post_wayback_v1_available

#### Input Parameters
* `url` - _required_ - A single URL to query.
* `timestamp` - _optional_ - Timestamp requested in ISO 8601 format. The following formats are acceptable:
 - YYYY
 - YYYY-MM
 - YYYY-MM-DD
 - YYYY-MM-DDTHH:mm:SSz
 - YYYY-MM-DD:HH:mm+00:00

* `callback` - _optional_ - Specifies a JavaScript function func, for a JSON-P response. When provided, results are wrapped as `callback(data)`, and the returned MIME type is application/javascript. This causes the caller to automatically run the func with the JSON results as its argument.

* `timeout` - _optional_ - Timeout is the maximum number of seconds to wait for the availability API to get its underlying results from the CDX server. The default value is 5.0.

* `closest` - _optional_ - The direction specifies whether to match archived timestamps that are before the provided one, after, or the default either (closest in either direction). Must be before, after, or either. May be overidden by individual requests.

    Possible values: either, before, after.
* `status_code` - _optional_ - HTTP status codes to filter by. Only results with these codes will be returned

    Possible values: 200, 201, 202, 203, 204, 205, 206, 300, 301, 302, 303, 304, 305, 306, 307, 308, 400, 401, 402, 403, 404, 405, 406, 407, 408, 409, 410, 411, 412, 413, 414, 415, 416, 417, 418, 421, 426, 428, 429, 431, 500, 501, 502, 503, 504, 505, 506, 507, 511.
* `tag` - _optional_ - The optional tag can have any value, and is returned with the results; it can be used to help collate input and output values.


## License

flowground :- Telekom iPaaS / archive-org-wayback-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
