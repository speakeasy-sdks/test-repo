<!-- Start SDK Example Usage [usage] -->
```python
import scorecard_test
from scorecard_test.models import shared

s = scorecard_test.ScorecardTest()

req = shared.Pet(
    id=596804,
    name='<value>',
)

res = s.pets.create_pets(req)

if res is not None:
    # handle response
    pass

```
<!-- End SDK Example Usage [usage] -->