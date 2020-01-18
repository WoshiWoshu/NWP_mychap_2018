# NWP_mychap_2018
Second year project in C in which the goal is to perform a challenge-handshake authentication protocol (CHAP) to an authen-ticating entity.
In other word to create a client that interact with an authenticating entity (the server).
It implements a low level protocol as a UDP client with different preliminary phases.

USAGE :

    Make.

    ./client -t -p -P.
    
    -t : Target Name.
    
    -p : Port.
    
    -P : Password.

EXEMPLE :

    > ./client -t localhost -p 4241 -P “epitech21”.

    Output: Secret: ‘Sh0k0b0n’.

    ./client -t localhost -p 4242 -P “wrong_password”.
    
    Ouput : KO.
