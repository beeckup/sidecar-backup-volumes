build:
	rm -rf backup.go || true
	rm -rf cleaner.sh || true
	rm -rf cron_script.sh || true
	cp  ../backup.go backup.go
	cp  ../cron_script.sh cron_script.sh
	cp  ../cleaner.sh cleaner.sh
	docker build -t beeckup/sidecar-backup-volumes:dev .
	rm -rf backup.go || true
	rm -rf cron_script.sh || true
	rm -rf cleaner.sh || true
