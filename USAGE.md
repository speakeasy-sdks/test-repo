<!-- Start SDK Example Usage [usage] -->
```python
import scorecard_test

s = scorecard_test.ScorecardTest()


res = s.pets.create_pets()

if res.status_code == 200:
    # handle response
    pass
```
<!-- End SDK Example Usage [usage] -->