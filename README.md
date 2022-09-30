# botosc

AWS Boto-like library for Outscale API. Manipulate objects instead of plain dicts.

## exemple:
```
import osc_sdk
from botosc.connector import Connector

connection = Connector(**osc_sdk.sdk.get_conf('my'))
connection.read_images()
```