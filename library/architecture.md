# Library architecture

```
library
 |
 ├─ category
     │
     ├─ <manufacturer name>_<part name>_<part number>
          ├─ datasheet.pdf
          ├─ design.FCStd       # Optional FreeCad design
          ├─ image.png
          ├─ thumbnail.step
          └─ part_info.yaml
```

### Part info format

```
name: <part name>
manufacturer: <manufacturer>
manufacturer_id: <part number>
lily_id: <erp part number>
```
