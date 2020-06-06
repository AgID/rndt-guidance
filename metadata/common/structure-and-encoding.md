## 2.1 Struttura e codifica dei metadati

<a name=C.1>**Requisito C.1** </a>- ```**metadata/2.0/req/common/xml-schema**```

I record di metadati devono essere codificati in formato XML conforme ad uno dei seguenti schemi XSD:

- [CSW2 AP ISO] XML Schema,

- [ISO 19139] XML Schema disponibile nel repository ISO,

- [ISO 19139] XML Schema disponibile nel repository degli schemi OGC.

Tutti e tre gli schemi indicati dichiarano lo stesso namespace [_http://www.isotc211.org/2005/gmd_](http://www.isotc211.org/2005/gmd).

Per i servizi deve essere utilizzato lo schema XSD disponibile nel repository degli schemi OGC. Questo schema rappresenta l&#39;implementazione XML dello Standard [ISO 19119] per i metadati dei servizi e dichiara il namespace [_http://www.isotc211.org/2005/srv_](http://www.isotc211.org/2005/srv).