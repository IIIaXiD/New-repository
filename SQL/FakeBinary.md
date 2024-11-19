
SELECT
  x,
  translate(x, '0123456789', '0000011111') as res
FROM fakebin