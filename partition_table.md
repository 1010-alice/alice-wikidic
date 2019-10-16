# Oracle Partition table 

## Range Partition
특정 컬럼 value에 따라 다른 파티션에 저장
```The data is distributed based on a range of values.```

 ex) 날짜 컬럼값을 월단위로 나눠 월별로 파티션에 따로 저장 가능
 

## Hash Partition
특정 컬럼 value에 따라 다른 파티션에 저장
An internal hash algorithm is applied to the partitioning key to determine the partition.

 ex) 날짜 컬럼값을 월단위로 나눠 월별로 파티션에 따로 저장 가능
 
 
 
## Interval Partition
특정 컬럼 value에 따라 다른 파티션에 저장
Extends the capabilites of the range method by automatically defining equi-partitioned ranges for any future partitions using an interval definition as part of the table metadata.

 ex) 날짜 컬럼값을 월단위로 나눠 월별로 파티션에 따로 저장 가능
 
 
 
