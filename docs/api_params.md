---
id: api_params
title: API Parameters
sidebar_position: 1
---

# Overview
Our backend is able to accept a number of parameters via URL, i.e., task parameters and session identifiers.

## Session identifiers
**activity_name**: 

  - possible values: `symbol-search`, `grid-memory`, `color-shapes`, `color-dots`

**admin_type**: qualtrics, metricwire

**study_id**: a study identifier (name)
* default is 'demo'. This will need to change to your study name before you get started. This will be requested by following the steps of the authorization guide.  

**session_id**: a session identifier
* For MetricWire this will be: `|*submissionSessionId*|`

**participant_id**: a participant identifier
* For MetricWire this will be: `|*participantUserId*|`

**api_key**: a valid API key
* If you are ready for your API key, please follow the **[Authorization Guide](https://github.com/m2c2-project/m2c2kit-integration-guides/blob/main/docs/authorization_guide.md#getting-started---authorization-to-access-data)** to get set up

**group**: a group indicator (str) - optional

**wave**: a wave indicator (str) - optional 

## Task parameters

However, although parameters are passed via URL, we still need to preserve type information to pass to m2c2kit. That happens by spelling the parameters **exactly** as noted in the links above, and the types need to be passed with a double colon (::) separator. For example, if I wanted 1 trial, I would specify the URL param as: `number_of_trials=1::int`.

See links below for all available parameters for each task: 

- [Grid Memory Schema](https://m2c2-project.github.io/m2c2kit/docs/schemas/grid-memory)
- [Color Dots Schema](https://m2c2-project.github.io/m2c2kit/docs/schemas/color-dots)
- [Color Shapes Schema](https://m2c2-project.github.io/m2c2kit/docs/schemas/color-shapes)
- [Symbol Search Schema](https://m2c2-project.github.io/m2c2kit/docs/schemas/symbol-search)

Available data types are:
- `int`
- `float`
- `boolean`
- `base64`
- `json`
- `uri`

## Example URL

The link below is an example of a task demo for Symbol Search, with 3 trials:

[https://prod.m2c2kit.com/m2c2kit/nt/index.html?activity_name=symbol-search&study_id=demo&api_key=demo&number_of_trials=3::int&show_quit_button=false::boolean&participant_id=None&session_id=XXX&admin_type=missing](https://prod.m2c2kit.com/m2c2kit/nt/index.html?activity_name=symbol-search&study_id=demo&api_key=demo&number_of_trials=3::int&show_quit_button=false::boolean&participant_id=None&session_id=XXX&admin_type=missing)
