SELECT id,
mod(base , factor) =0 
AS res
FROM kata;
//---------------------
select id, base % factor = 0 as res from kata;