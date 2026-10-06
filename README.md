# Macelleria Bonetti

Prototipo frontend di negozio online per una macelleria di quartiere (Torino, attività di fantasia).
Frontend prototype of an online storefront for an Italian butcher shop. All copy is in Italian.

## Cosa c'è / What's in it
- Schema interattivo dei tagli del bovino che filtra il banco
- Banco con i tagli disegnati in codice (niente foto stock)
- **Su misura**: configuratore della bistecca (spessore in cm, razza, frollatura, bilancia, animazione di incarto)
- Cassette (una tantum o in abbonamento)
- Cassa mobile in 3 passi: ritiro al banco / in auto / consegna, orari reali con pausa pranzo, Satispay, carta o pagamento al ritiro
- Avvisi d'ordine su WhatsApp/SMS al titolare (simulati)

Payments, WhatsApp/SMS alerts and inventory are simulated in the browser; the backend is a separate phase.

## Deploy
Static site, no build step. In Vercel: import this repo, framework preset **Other**, no build command, output directory `.`.
