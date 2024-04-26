 --Display 7 segmentos
 --26/05/2024
 --Querido Professor  Dalton
 
 LIBRARY IEEE;
 USE IEEE.STD_LOGIC_1164.all;
 USE IEEE.STD_LOGIC_ARTIH.all;
 USE IEEE.STD_LOGIC_USIGNED.all;
 
 Entity proj.... is
    port(
    --pinos de entrada
    SW: IN STD_LOGIC_VECTOR(3 DONTO 0);
    --pinos de saída
    HEX: out STD_LOGIC_VECTOR(17 DONTO 0);
    );
END Entity

ARCHITECTURE est OF proj.... is

BEGIN
    PROCESS(SW)
    BEGIN
        HEX0(0) <= NOT(((NOT(SW(1)))AND(NOT(SW(3)))) OR ((NOT(SW(0))ANDSW(2))) OR ((NOT(SW(0)))AND(SW(1))AND(SW3)) OR ((SW(1))AND(SW(2))) OR ((SW(0))AND(NOT(SW(1)))AND(NOT(SW(2)))) OR 
                    ((SW(0))AND(NOT(SW3))));
        HEX0(1) <=
        HEX0(2) <= NOT(((NOT(SW(0)))AND(NOT(SW(2)))) OR ((NOT(SW(0)))AND(SW(3))) OR ((NOT(SW(2)))AND(SW(3))) OR ((NOT(SW(0)))AND(SW(1))) OR ((SW(0))AND(NOT(SW(1)))));
        HEX0(3) <=
        HEX0(4) <=NOT(((NOT(SW(1)))AND(NOT(SW(3)))) OR ((SW(2))AND(NOT(SW(3)))) OR ((SW(0))AND(SW(2))) OR ((SW(0))AND((SW(1)))));
        HEX0(5) <=
        HEX0(6) <=NOT(((NOT(SW(1)))AND(SW(2))) OR ((SW(2))AND(NOT(SW(3)))) OR ((NOT(SW(0)))AND(SW(1))AND(NOT(SW(2)))) OR ((SW(0))AND((NOT(SW(1))))) OR ((SW(0))AND((SW(3))))); 
    END PROCESS;
END exit;


    
