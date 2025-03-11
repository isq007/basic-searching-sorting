# Bubble Sort

START
  INPUT array A of size N
  FOR i FROM 0 TO N-1 DO
      FOR j FROM 0 TO N-i-1 DO
          IF A[j] > A[j+1] THEN
              SWAP A[j] and A[j+1]
          ENDIF
      ENDFOR
  ENDFOR
PRINT sorted array
END
