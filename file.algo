ALGORITHM SENTENCE

VAR
nbv,nbw,nbc :=INTEGER;
sentc := STRING[];

BEGIN

nbc := 0;
nbw := 0;
nbv := 0;

write("this is a sentence.")

Read(sentc)

REPEAT
IF(sentc[nbc]="") THEN
nbw := nbw+1;
END_IF

IF (sentc[nbc] in ["a","e","u","i","o","y"]) THEN
nbv := nbv+1;

END_IF

nbc := nbc+1;

UNTIL (sentc[nbc]=".")

write ("The number of characters is",nbc+1)
write ("The number of word is",nbw+1)
write ("The number of vowels is",nbv)

END