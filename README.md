# localDiscord
è un semplice progetto in C che simula il comportamento di una chat multiprocess (server–client) utilizzando sole named pipes (FIFO), unnamed pipes, fork e select(), senza thread né segnali; ogni utente  ha una FIFO privata e comunica con il server tramite una FIFO condivisa le operazioni impartite
