# Blobaa DID Method Specification v1.0

## Method-specific DID syntax

The following ABNF defines the blobaa-specific DID scheme:

```ABNF
blobaa-did = "did:blobaa:" blboaa-identifier
blobaa-identifier = [ ardor-network ":" ] ardor-tx-hash
ardor-network = "m" / "t"
ardor-tx-hash = 64HEXDIG
```



did:bba:m:f30e8cff75e5111da9943c123733d697120914bbef1b5010732ad409cbf29ee2


https://tools.ietf.org/html/rfc5234

http://cryptocoinjs.com/modules/misc/bs58/




## CRUD

### Create

![](images/out/images/src/plantuml/did-create.svg)


### Read

![](images/out/images/src/plantuml/did-read.svg)


### Update

![](images/out/images/src/plantuml/did-update.svg)


### Deactivate

![](images/out/images/src/plantuml/did-delete.svg)

