## Appendix Static Conformance Requirements (NORMATIVE)

The notation used in this appendix is specified in [SCRRULES].

```
The following is a model of a set of SCR tables.  DELETE THIS COMMENT
```

### SCR for XYZ Client
<table>
    <caption>Bootstrap Interface</caption>
    <thead>
        <tr>
            <th>Item</th>
            <th>Function</th>
            <th>Reference</th>
            <th>Requirement</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>XYZ-C-001-M</td>
            <td>Something mandatory</td>
            <td>Section x.y</td>
            <td>(XYZ-C-004-O OR XYZ-C-003-M) AND XYZ-C-002-O</td>
        </tr>
        <tr>
            <td>XYZ-C-002-O</td>
            <td>Something optional</td>
            <td>Section x.y</td>
            <td></td>
        </tr>
        <tr>
            <td>XYZ-C-003-M</td>
            <td>Dependencies on ZYX</td>
            <td>Section x.y</td>
            <td>ZYX:MCF</td>
        </tr> 
        <tr>
            <td>XYZ-C-004-O</td>
            <td>Dependencies on ZYX</td>
            <td>Section x.y</td>
            <td>ZYX:OCF</td>
        </tr>
    </tbody>
</table>

### SCR for XYZ Server
<table>
    <caption>Bootstrap Interface</caption>
    <thead>
        <tr>
            <th>Item</th>
            <th>Function</th>
            <th>Reference</th>
            <th>Requirement</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>XYZ-S-001-M</td>
            <td>Something mandatory</td>
            <td>Section x.y</td>
            <td>XYZ-S-004-O OR XYZ-S-002-O OR XYZ-S-003-M</td>
        </tr>
        <tr>
            <td>XYZ-S-002-O</td>
            <td>Something optional</td>
            <td>Section x.y</td>
            <td></td>
        </tr>
        <tr>
            <td>XYZ-S-003-M</td>
            <td>Dependencies on ZYX</td>
            <td>Section x.y</td>
            <td>ZYX:MCF</td>
        </tr> 
        <tr>
            <td>XYZ-S-004-O</td>
            <td>Dependencies on ZYX</td>
            <td>Section x.y</td>
            <td>ZYX:OCF</td>
        </tr>
    </tbody>
</table>
