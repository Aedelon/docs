# Méthode getblockhash

Retourne la valeur de hashage correspondant au bloc de l'index indiqué.

## Paramètre de la méthode

index : Index du bloc.

## Exemple

Requète :

```json
{
   "jsonrpc": "2.0",
   "method": "getblockhash",
   "params": [10000],
   "id": 1
}
```

Réponse :

```json
{
   "jsonrpc": "2.0",
   "id": 1,
   "result": "4c1e879872344349067c3b1a30781eeb4f9040d3795db7922f513f6f9660b9b2"
}
```