# virtualization
Modul Virtualisierung

## pythonwebserver

```bash
docker build -f Dockerfile . -t pythonwebserver
```
```bash
sudo docker run --rm -p 8000:80 --name pythonwebserver pythonwebserver
```
