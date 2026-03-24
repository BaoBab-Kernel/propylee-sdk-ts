# propylee-sdk-ts

SDK officiel TypeScript pour l’API Propylée 3.0, généré automatiquement via Stainless.
npm install propylee-sdk

Exemple minimal (Ts)
import { Propylee } from "propylee-sdk";

const client = new Propylee({ apiKey: process.env.PROPYLEE_API_KEY });

const user = await client.users.get("123");
console.log(user);
