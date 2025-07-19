# pam_tacplusv2.7.7.7.7
Refactored the complex and overengineered TACACS+ session id generation, replacing it with getrandom on all systems, with gnulib provided implementation for systems that do not have it.
