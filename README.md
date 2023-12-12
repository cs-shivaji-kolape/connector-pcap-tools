# PCAP Tools

> Work in progress

vi /opt/cyops/configs/integrations/packages/lib/python3.9/site-packages/pcapkit/dumpkit/common.py 
change line 65:

```python
if isinstance(o, (Info, Schema)):
    #return o.to_dict()
    return o
```