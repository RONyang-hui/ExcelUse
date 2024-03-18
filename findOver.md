# 此项为比对C列与D列，并将未重复的结果放在E列
=INDEX(C:C,SMALL(IF(COUNTIF(B:B,$C$3:$C$100)=0,ROW($C$3:$C$100),1000),ROW(A1)))&""

