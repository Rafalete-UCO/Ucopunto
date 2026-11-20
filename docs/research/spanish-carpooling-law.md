# Spanish carpooling law: cost-sharing cap and what counts as profit

Research for issue #2 (child of wayfinder map #1). Researched 2026-11-20 against
the consolidated texts on the BOE. Not legal advice. Have a lawyer or tax
adviser confirm the open points below before launch.

## TL;DR

- **Carpooling now has an explicit legal definition.** Ley 9/2025 de Movilidad
  Sostenible (in force 5 Dec 2025) defines "servicios de movilidad colaborativa
  o carpooling": shared trips in a passenger car, made **free of charge except
  for cost-sharing**. It also amended LOTT art. 62.3 so that these trips count
  as *transporte privado particular*. That means no transport licence is needed.
- **The platform may charge.** Both texts say the intermediation platform "puede
  hacerlo a título oneroso", so a platform fee or commission is expressly lawful.
  The non-profit rule applies to the **driver**, not to the intermediary.
- **No per-km cap is fixed yet.** LOTT art. 62.3 lets the Government set a
  "baremo de costes" by regulation, to mark where a driver's payment turns the
  trip into public transport. No such baremo was found in the BOE as of
  2026-11-20, including RD 182/2026, the latest ROTT amendment. Today the test
  is qualitative: payment must not exceed the driver's actual trip costs.
- **Useful reference numbers**, neither of them a legal cap:
  - The BlaBlaCar ruling (2017) accepted suggested prices of **€0.06–0.09/km**
    *per passenger*.
  - The tax-exempt mileage allowance is **€0.26/km** (RIRPF art. 9 as revised
    by Orden HFP/792/2023). This is a defensible ceiling for the *whole car's*
    running cost per km.
- **Profit for the driver** = anything above their share of the actual trip
  costs: fuel, tolls, wear. If that happens repeatedly, the driver is doing
  unlicensed public transport, a *muy grave* infraction under LOTT art. 140.1,
  fined €4,001–6,000 (art. 143.1.i).
- **Insurance:** the ordinary compulsory motor insurance (SOA) already covers
  passengers as third parties. The Seguro Obligatorio de Viajeros applies only
  to *public collective* transport, so it does not apply here.
- **Tax:** no binding DGT ruling on carpooling receipts was found. Pure cost
  reimbursement produces no net gain. Any surplus or incentive is taxable
  income. The platform's fee is a service subject to VAT, as noted in the
  BlaBlaCar ruling.
- **Andalusia:** no regional carpooling rule was found. The state LOTT and Ley
  9/2025 framework applies.
- **Possible funding source:** the energy-savings certificate (CAE) catalogue
  includes card **TRA040 "Movilidad colaborativa en trayectos rutinarios"**,
  updated in August 2026. A carpooling platform run by a legal entity can earn
  certificates for the energy its users save.

## 1. Legal classification

### LOTT art. 101.1.a (private transport by individuals)

> "En ningún caso, salvo el supuesto de percepción de dietas o gastos de
> desplazamiento para su titular, el transporte particular puede dar lugar a
> remuneraciones dinerarias directas o indirectas."

Private transport by individuals needs no administrative authorisation (art.
101.2). ROTT art. 154 adds that it must be done in a *vehículo de turismo*
(passenger car).

- LOTT consolidated: https://www.boe.es/buscar/act.php?id=BOE-A-1987-17803#a101
- ROTT consolidated (RD 1211/1990): https://www.boe.es/buscar/act.php?id=BOE-A-1990-24442#a154

### LOTT art. 62.3, as amended by Ley 9/2025 (DF 4ª.5), in force 05/12/2025

> "Los servicios de movilidad colaborativa, entendidos como aquellos efectuados
> a título no oneroso excepto por la compartición de gastos, en los que varios
> usuarios comparten un vehículo de turismo en un mismo viaje, se consideran
> transportes privados particulares. En estos servicios, los usuarios pueden
> ponerse en contacto a través de una plataforma de intermediación, pudiendo
> las empresas que realizan esta actividad de intermediación hacerlo a título
> oneroso. Con el fin de delimitar los supuestos en los que la contraprestación
> recibida por el conductor o conductora pueda implicar la realización de un
> transporte público, podrá establecerse reglamentariamente un baremo de costes
> para estos servicios de movilidad colaborativa."

- https://www.boe.es/buscar/act.php?id=BOE-A-1987-17803#a62

### Ley 9/2025 de Movilidad Sostenible, art. 2.1.x (definition)

This definition repeats the one above. It adds that, for the purposes of the
LOTT, carpooling services are *transportes privados particulares*. The preamble
says the reform makes it possible to separate carpooling by regulation from
public transport done for third parties.

Ley 9/2025 also *promotes* carpooling:

- it lists carpooling in the integrated mobility system (art. 4);
- workplace mobility plans must consider shared and collaborative solutions;
- large workplaces with more than 1,000 workers in areas of more than 500,000
  inhabitants must promote collaborative mobility.

A university can cite this to justify the app.

- https://www.boe.es/buscar/act.php?id=BOE-A-2025-24545

## 2. How the cost-sharing cap is computed

**There is no statutory per-km figure as of 2026-11-20.** LOTT art. 62.3 allows
a regulatory *baremo de costes* but does not require one. The searches found
none:

- RD 182/2026 (BOE-A-2026-5716) amended the ROTT in March 2026, but its text
  contains no "colaborativa" or "baremo" provisions;
- no draft was found on the BOE.

Until a baremo exists, the legal test is the one in art. 62.3 and art. 101:
the driver may receive only *compartición de gastos*, meaning the costs of the
trip. Defensible reference points, in increasing order of generosity:

| Reference | Figure | Source | Notes |
|---|---|---|---|
| BlaBlaCar suggested price, accepted by the court | €0.06–0.09 / km **per passenger** | Juzgado de lo Mercantil nº 2 Madrid, Feb 2017 (CGPJ press release) | The court contrasted it with the €0.19/km official mileage allowance of the time and concluded it was not aimed at profit. |
| Official IRPF tax-exempt mileage allowance | **€0.26 / km** per vehicle (plus tolls and parking) | RIRPF (RD 439/2007) art. 9.A.2.b, revised by Orden HFP/792/2023 (BOE-A-2023-16461) | This is the State's own estimate of a private car's running cost per km. It works as a ceiling for the **total** collected from all passengers on a trip. |

**Suggested app rule:**

- price per passenger ≤ (€0.26 × trip km + tolls) ÷ (passengers + 1 driver);
- the total collected per trip must never exceed €0.26 × km + tolls.

The ÷ (passengers + 1) part keeps the driver paying their own share, which is
the safest reading of "compartir gastos". Make the €/km rate a single setting,
so that it can follow a future baremo.

- CGPJ press release on the BlaBlaCar ruling:
  https://www.poderjudicial.es/cgpj/es/Poder-Judicial/Noticias-Judiciales/El-juez-desestima-la-demanda-contra-Blablacar--al-entender-que-no-existe-competencia-desleal
- The Audiencia Provincial de Madrid upheld the ruling on appeal in 2019. It
  found that BlaBlaCar provides an information-society service, not transport.
  This comes from secondary coverage; the CENDOJ text was not retrieved.
  https://elderecho.com/la-audiencia-provincial-ratifica-que-blablacar-no-supone-competencia-desleal-para-el-autobus
- RIRPF consolidated: https://www.boe.es/buscar/act.php?id=BOE-A-2007-6820

## 3. What counts as profit

**Driver.** Any payment beyond their share of the trip's actual costs is
profit. At that point the trip stops being *transporte privado particular* and
becomes public transport done without a licence:

- LOTT art. 140.1 makes "la realización de transportes públicos careciendo del
  título habilitante" a *muy grave* infraction;
- art. 143.1.i sets the fine at €4,001–6,000;
- art. 143.1.j raises it to €6,001–18,000 for repeat offenders.

Factors that make profit more likely:

- prices above cost;
- drivers making trips they would not otherwise make, purely to carry
  passengers;
- running it as a habitual business.

The BlaBlaCar ruling stressed that the driver makes the trip anyway, on their
own account, and that the platform removes users who seek profit.

**Platform.** The law expressly allows the intermediary to charge ("a título
oneroso"), so a platform fee is not "profit" in the LOTT sense. The client's
model is consistent with this: the passenger pays the fee on top of the cost
share, and none of the fee goes to the driver. The platform's non-profit
status is a matter of its own legal form, such as an association or a
university service, not a LOTT requirement.

## 4. Platform commission and payments

- **A commission is allowed** (LOTT art. 62.3; Ley 9/2025 art. 2.1.x).
- **Keep the fee separate from the driver's share** in the data model and on
  receipts. Fee proceeds must never reach the driver, or the driver's payment
  would exceed cost sharing.
- **VAT:** the platform's fee is an intermediation service, and the BlaBlaCar
  ruling notes that the platform paid VAT on its commission. Whether a
  university or non-profit operator charges 21% VAT depends on its legal form.
  Confirm this with a tax adviser.
- **Payment flow:** the platform collects money and passes the cost share on to
  the driver. That can be a regulated payment service under Real Decreto-ley
  19/2018 (PSD2 transposition). The usual approach is a licensed PSP's
  marketplace product (split payments, connected accounts), so that the
  platform never holds the funds. Not researched in depth here; flagged as a
  follow-up.

## 5. Insurance

- **The compulsory motor insurance (SOA)** covers liability towards third
  parties, and passengers are third parties. Its exclusions (RDL 8/2004 art. 5)
  cover only:
  - the driver's own injuries;
  - damage to the vehicle and to goods carried in it;
  - stolen vehicles.

  Injured carpool passengers are therefore covered by the driver's ordinary
  policy.
  https://www.boe.es/buscar/act.php?id=BOE-A-2004-18911#a5
- **The Seguro Obligatorio de Viajeros** (RD 1575/1989 arts. 1, 2, 4) covers
  only users of *transporte público colectivo*. It does not apply to carpooling
  as *transporte privado particular*.
  https://www.boe.es/buscar/act.php?id=BOE-A-1989-30474
- **Practical point:** some private policies limit use to "private use, not for
  hire". Cost sharing within the law is private use, but the app should tell
  drivers to check their policy. It should also require a valid ITV, a driving
  licence and insurance, and record that the driver has confirmed them.

## 6. Tax

- **Driver (IRPF):** no DGT binding consultation on carpooling receipts was
  found in the searches. Under general IRPF principles, reimbursing actual
  costs yields no net income. Amounts above cost, or incentives paid by the
  platform, are taxable. The Tribbu platform, for example, treats its own
  incentives as a *ganancia patrimonial*, but that is the operator's own
  position. The €0.26/km figure is a sensible way to show that receipts did not
  exceed costs.
- **Platform reporting (DAC7, Ley 13/2023):** digital platforms must report
  sellers' "relevant activities" for consideration. HMRC's guidance uses
  ride-sharing as an example and notes that the amounts paid cannot exceed the
  cost of travel, so the seller makes no profit. Whether pure cost-sharing
  carpooling is reportable in Spain is unconfirmed; check it with AEAT or an
  adviser.
  https://www.gov.uk/hmrc-internal-manuals/international-exchange-of-information/ieim901300

## 7. Andalusia

No Andalusian rule specific to carpooling was found. The Anteproyecto de Ley
Andaluza de Movilidad Sostenible (2016–2020) does not appear to have been
enacted. Ley 2/2003 covers urban and metropolitan *public* transport. Interurban
private transport falls under the state LOTT, as interpreted above.

## 8. Funding opportunity: energy-savings certificates (CAE)

The Resolución de 30 de julio de 2026 (BOE-A-2026-16993) updated card **TRA040
"Movilidad colaborativa en trayectos habituales de corta distancia"** in the
catalogue of standardised energy-efficiency measures (RD 36/2023, Orden
TED/845/2023). A carpooling platform run by a legal entity can get energy
savings certified and sell them. Conditions include:

- users who are private individuals, not transport professionals;
- identity verification;
- daily limits on km and trips;
- traceable trip data;
- an independent audit;
- GDPR notice to users;
- the incentive shared equally among the users who generated the savings.

https://www.boe.es/boe/dias/2026/08/04/pdfs/BOE-A-2026-16993.pdf

## Open points for a professional

1. Has a *baremo de costes* been issued since 2026-11-20? Check the BOE and the
   Ministry of Transport's *proyectos normativos* page.
2. VAT treatment of the fee if a university or non-profit runs the platform.
3. Whether the payment gateway setup needs a payment-institution licence under
   RDL 19/2018.
4. Whether DAC7 reporting applies to pure cost-sharing trips.
