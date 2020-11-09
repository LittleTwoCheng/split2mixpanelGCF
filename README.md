This is a Google Cloud Function that acts as a Split impressions webhook:  parse the impressions to create MixPanel events, base64 encode them, and send them to the MixPanel events endpoint.  Available elsewhere as an AWS Lambda.

## Runtime environment variables

|  Name     | Value      |
|  ---  |  ---  |
|  MIXPANEL_TOKEN     |   Your Mixpanel Project Token(can be found under https://mixpanel.com/settings/project/{project_id})    |
|  VERBOSE     |   1 or 0; For debug propose. Detail please see https://developer.mixpanel.com/reference/events#track-event    |

