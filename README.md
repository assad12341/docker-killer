# docker-killer
Docker Knocker
Exploits Unauth Docker API (Docker Remote API Detection)


usage: 

exploit.py [-h] --target TARGET
--attack {dump-shadow,dump-passwd,exfil-ssh,inject-key,reverse-shell}
[--user USER] [--pubkey PUBKEY] [--listen-port LISTEN_PORT]
[--reverse-port REVERSE_PORT] [--attacker-ip ATTACKER_IP]
the following arguments are required: --target, --attack
