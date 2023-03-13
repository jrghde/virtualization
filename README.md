# virtualization
Modul Virtualisierung

## salidu
```bash
docker-compose up -d
docker cp ./salidu.sh bashscriptContainer:/tmp/salidu.sh
docker exec bashscriptContainer bash -c ". /tmp/salidu.sh" > salidu.out
```

## pythonwebserver
```bash
docker build -f Dockerfile . -t pythonwebserver
sudo docker run --rm -p 8000:80 --name pythonwebserver pythonwebserver
```
