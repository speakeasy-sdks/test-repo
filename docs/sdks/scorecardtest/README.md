# ScorecardTest SDK


## Overview

### Available Operations

* [create_run](#create_run) - Create a test run

## create_run

Create a test run

### Example Usage

```python
import scorecard_test


s = scorecard_test.ScorecardTest()


res = s.scorecard_test.create_run()

if res.status_code == 200:
    # handle response
```


### Response

**[operations.CreateRunResponse](../../models/operations/createrunresponse.md)**

