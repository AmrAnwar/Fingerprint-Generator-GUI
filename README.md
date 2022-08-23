# Fingerprint-Generator-GUI
GUI for different machine learning fingerprint generator models
![Canvas generator](/images/f_7.png)

## Run from docker 
```
cd fpgen
docker build --tag fpgen-frontend --progress=plain .
docker run -p 80:80 fpgen-frontend
```
## Development server
- firstly go in `cd fpgen`
- run `npm install`
- Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.