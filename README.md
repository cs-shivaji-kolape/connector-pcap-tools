# PCAP Tools

> Work in progress

vi /opt/cyops/configs/integrations/packages/lib/python3.9/site-packages/pcapkit/dumpkit/common.py 
change line 65:
     64             if isinstance(o, (Info, Schema)):
     65                 #return o.to_dict()
     66                 return o