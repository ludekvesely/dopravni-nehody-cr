### Database of car accidents in the Czech Republic (2007 - 2013)

This is Docker image with Elasticsearch and Kibana installed. Elasticsearch is filled with data downloaded from http://pcr.jdvm.cz/pcr/. There are data from 2007 to 2013. After run port 5601 is exposed. Publish this port and point web browser on it - you should see default dashboard in Kibana.

You can see demo here: [http://nehody.ludekvesely.cz](http://nehody.ludekvesely.cz)

![Default Kibana dashboard](http://www.ludekvesely.cz/content/images/2015/05/kibana.png)

---

### Databaze dopravnich nehod CR 2007 - 2013


Docker image s nainstalovanymi Elasticsearch a Kibana. Po spusteni je Kibana dostupna na portu 5601. V Kibane lze prohlizet grafy, tabulky, filtrovat vizualizace podle ruznych parametru.



Stazeni a spusteni:

```
docker pull ludekvesely/nehody:latest
docker run -p 5000:5601 ludekvesely/nehody:latest
```



Po spusteni je Kibana dostupna na portu 5000. Vice informaci na [www.ludekvesely.cz/databaze-dopravnich-nehod-cr/](http://www.ludekvesely.cz/databaze-dopravnich-nehod-cr/).
