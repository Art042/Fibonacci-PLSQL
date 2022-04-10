/*
Criar um bloco PL/SQL para imprimir a sequência de Fibonacci: 1 1 2 3 5 8 13 21 34 55.
*/

DECLARE
 V_SEQ NUMBER(10) := 11
 V_1 NUMBER(2) := 1;
 V_2 NUMBER(2) := 1;
 V_3 NUMBER(2) := 0;
BEGIN
 FOR V_I IN 1..V_SEQ LOOP
 V_1 := V_2;
 V_2 := V_3;
 DBMS_OUTPUT.PUT_LINE(V_3);
 V_3 := V_1 + V_2;
 END LOOP;
END;
