PATHC = srcs/docker-compose.yml

up:
	docker compose -f $(PATHC) up -d --build

down:
	docker compose -f $(PATHC) down

cdown:
	docker compose -f $(PATHC) down --rmi all -v

stop:
	docker compose -f $(PATHC) stop

start:
	docker compose -f $(PATHC) start

restart:
	docker compose -f $(PATHC) restart

pause:
	docker compose -f $(PATHC) pause
