# dbms_plsql1 adding
CREATE DEFINER=`root`@`localhost` PROCEDURE `addition`()
BEGIN
declare a,b,c int(4);
set a=25,b=40;
set c=a+b;
select c;
END
