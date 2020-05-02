DECLARE variable kecepatan 
DECLARE variable penumpang

SET kecepatan = 20

IF penumpang lower or equal 4 
    IF penumpang equal 4
        SET kecepatan - 7
    ELSE IF penumpang greater than 2
        SET kecepatan - 5
    ELSE
        SET kecepatan - 2

ELSE
    DISPLAY "Over Capacity"

DISPLAY kecepatan