## FOEX Markup Docs

> Note: This is a general note.

!> This is an **important** note.

?> This is a general tip

<h4>HTML is also allwed. This is an h4 element.</h4>

## Code

```sql
SELECT PRODUCT_ID
     , PRODUCT_NAME
     , PRODUCT_DESCRIPTION
     , CATEGORY
     , LIST_PRICE
     , CASE PRODUCT_AVAIL
        WHEN 'Y' THEN 'Yes'
        WHEN 'N' THEN 'No'
       END AS PRODUCT_AVAILABLE
  FROM DEMO_PRODUCT_INFO;
 ```

```plsql
declare
    l_var number;
begin
    dbms_output.put_line('test');
end;
/

```

```javascript
var test = 10;
console.log(test);
```

```bash
> sqlplus /nolog
```
