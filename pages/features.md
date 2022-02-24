# Features
--- 
## Project Detail

Shows a short summary of a project. Here are some of the details/data shown by this feature/page.

- Name
- Description
- Fund Source
- System/Category
- Amount in (PhP)
- Expenditure Sources
- Expenditures
- Contract or List of Contracts


## Contract Detail

Short a detailed information about the contract. Here are some of the details/data shown by this feature/page.

- Contract ID
- Description
- Start Date / Contract Effectivity
- Duration
- Expiry Date
- Revised Expiry Date
    - Auto calculated based on suspensions
- Original Amount
- Revised Amount
    - Reflected based on variation orders
- Contractor
- Project In Charge
- Contract S-Curve

## Contract Suspension and Resumptions

![Suspension and Resumption](img/suspension-resumption.png)

This page let the user suspend a contract and resumes it. It lists all the suspension and resumption orders for the contract. Any input here is reflected in the contract `s-curve` and the `revised target completion date`.

## Contract Summary


## Contract Timeline


## Contract S-Curve

![S-Curve Sample](img/s-curve-sample.png)

In inputting the s-curve data, up to two users are ideally involved, 1st is the `admin` who inputs the original projected accomplishments and the `project-in-charge` that enters the progress accomplishments by a certain period intervals.

The s-curve in `PSMS` reflects the revised projected curve (shown by the red curve), which was automatically calculated by interpolating with the suspensions and resumptions.

## Physical Features



## Contracts Summary Per CY


## Summary of Negative Slippage Per Cy


## Projects Summary Per CY


## Projects Summary Per Fund Source Per CY