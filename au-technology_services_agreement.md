# Technology Services Agreement

`Purpose` This agreement covers technology services like:

- software as a service (SaaS);
- infrastructure as a service (IaaS);
- managed services; and
- web hosting.

`Party 1 Name` Contractor

`Party 2 Name` Customer

`Jurisdiction` Australia

## Service access

Contractor grants the Customer a {{territory}} [restricted licence](https://github.com/lawpatch/au-ip_license/blob/b109a2c8039df0fb564719810705b5b0f85e7593/au-license_ip_restrictive.md) to use the Service for the Agreement's duration.

## Agreement length

https://github.com/CodePact/au-components/blob/master/agreement_duration.md

## Calculation of payment

https://github.com/CodePact/au-components/blob/master/payment_calculation.md

## Payment method

https://github.com/CodePact/au-components/blob/master/payment_method.md

## Third party control

Customer agrees that parts of the Services are controlled by third party contractors, including:

{{third party suppliers}}

## Setup

Let's make clear who's responsible for setting up the services - it can take a great deal of time and effort.  Best that everyone's on the same page about who's responsible.

### Contractor does all the setup.

Contractor is responsible for the setup and installation of the Services.

### Contractor does all the setup except for certain tasks.

Contractor is responsible for the setup and installation of the Services, except for:

{{setup exceptions}}

### Contractor does none of the setup.

Customer is entirely responsible for the setup and installation of the Services.

## Support and maintenance

It's a good idea for a Customer to know just how much help you're willing to provide for them to use the services.  Writing a _Support Policy_ is one way to do this.

### Contractor will provide support based on the Support Policy.

Contractor will provide support and maintenance as described by the Support Policy.

### Contractor will provide ad-hoc support based on its discretion.

Contractor will provide support and maintenance to the Customer at its discretion.

### Contractor will provide support based on the Work Scope.

Contractor will provide support based on the details described in the Work Scope.

## Intellectual property protection

- Contractor reserves the right to alter any element of the Product IP at its discretion.
- Customer agrees not to reverse engineer any part of the Product IP.
- No licence is granted over any intellectual property in the Product IP unless explictly described in the Agreement.

## Failure to pay

If the Customer fails to pay any amount due under the Agreement more than {{shut off period}}, the Contractor may immediately, at its discretion:
- charge Client at an interest rate of interest equal to the <a href="https://www.ato.gov.au/Rates/General-interest-charge-(GIC)-rates/">ATO GIC Rate</a>; and
- suspend the provision of any part of the Services to Client.

## Confidentiality

https://github.com/CodePact/au-components/blob/master/confidentiality.md

## Use of service

Customer undertakes to use the Service:

- in accordance with the law at all times; and
- only in ways that the Service was designed to be used.

Customer undertakes not to use the Service:

- to bully, insult or harass people; and
- in assosciation with malware or pornographic material.

## Privacy

Customer represents and warrants that it is in full compliance with its obligations under any applicable privacy law in its use of the Services.

## Data disclosure

Contractor reserves the right to disclose Data to:

{{disclosure parties}}

## Data uploaded

When a customer contracts with a technology provider, they often upload data to services controlled by the technology provider.

The data uploaded can be really valuable.  Everyone needs to be clear about how that data can be used by the technoogy provider.

### Client provides an expansive licence over the Data for the Contractor to provide the Services.

Client provides an [expansive licence](https://github.com/lawpatch/au-ip_license/blob/bb178c5e86fec053f249c72cb4d6cd56af88825b/au-license_ip.md) to Contractor in order to provide the Services.

## Limitation

https://github.com/CodePact/au-components/blob/master/limitation.md

## Covering costs

https://github.com/CodePact/au-components/blob/master/indemnity.md

## Agreement changes

https://github.com/CodePact/au-components/blob/master/agreement_changes.md

## Cancellation for breach

https://github.com/CodePact/au-components/blob/master/cancel_breach.md

## Cancellation for convenience

https://github.com/CodePact/au-components/blob/master/cancel_convenience.md

## Necessary bureaucracy

https://github.com/CodePact/au-components/blob/master/end_agreement.md

## Definitions

### Agreement
means the agreement arising between the parties in accordance with this document and the other documents referred to by this document.

### Confidential Information
means any information disclosed by the Customer to the Contractor in connection with the Services, not including information that:

- is known to the Contractor at the time of disclosure;
- is or becomes publicly accessible; or
- is provided to the Contractor by a third party,

unconnected with a breach of the Agreement by either party.

### Data
means any data or information conveyed to the Service by the Customer.

### Product IP
means the intellectual property in {{product intellectual property}}.

### Service, Services
means {{services description}}.

### Support Policy
means the document entitled {{support policy name}} at {{support policy URL}}.

### Term
means {{renewing period}}.

### Work Scope
means {{work scope}}.

## Variables

#### billing cycle period

month

`Guidance` Fill in this variable with a time period for the billing cycle. It’s great to get paid weekly, but you have to issue an invoice before you get paid. The billing cycle period is a balance between keeping your cash flow regular and the administrative overhead of issuing the invoices required to get paid.

#### cancellation notice period

`Guidance` Fill in this variable with the time period you want to provide notice of cancellation within. 

#### completion amount

50% of the total amount payable for the Services

`Guidance` The completion amount is the money paid after the completion of the services. It is usually defined as a percentage amount of the overall cost of the development services under the agreement.

#### deposit amount

50% of the total amount payable for the Services [OR] $ DOLLAR_AMOUNT

`Guidance` The deposit is a non-refundable upfront payment for the services. It is usually defined as a percentage amount of the overall cost of the development services under the agreement. You could also use an amount, though.

#### disclosure parties

- a government or regulatory agency requesting it;
- facilitate a sale transaction in relation to the Contractor's business;
- any contractor providing a good or service used to provide the Services;
- its lawyers, insurance brokers or accountants; and
- any related entity.

#### fees table

| Work Description | Amount
|----------------------|--------
| Visual design for the app called "Example App" | $ 3,000
| DESCRIBE SERVICE | $ AMOUNT

`Guidance` Fill in the [markdown table](https://help.github.com/articles/github-flavored-markdown/) with the cost components of the services. In the left column, describe the service, and in the right column, describe the price as a dollar value.

#### fees url

`Guidance` Provide the url of the page that you set out your fees in.

#### governing law state

New South Wales

`Guidance` This is the state that you will go to court in if there’s legal action under this document. It’s usually better to have a "home court" advantage. If your business is in New South Wales, make the forum the New South Wales courts.

#### indemnified risk list

[PARTY RISKS]

- Customer's breach of the Agreement;
- any negligent act of the Customer connected with the Services;
- third party reliance on the Services under a contract with the Customer;
- Customer's use of the Services in connection with unlawful activity;

[DATA LAW]

- Customer's breach of any privacy law;
- Customer's breach of any law in connection with spam;
- Customer's storing of any third party data on the Services;
- a third party pursuing a right conferred by privacy law;

[INTELLECTUAL PROPERTY]

- any legal action taken by a third party alleging intellectual property infringement by the Customer in connection with the Services.

#### limitation amount

the amount paid to Contractor by the Customer in exchange for the Services [OR] $AMOUNT

`Guidance` Describe the amount of money that the customer can sue the contractor for. The example text allows the customer to get a full refund, since the Contractor can sue for the amount paid for the services by the customer. You can describe the amount or put a specific dollar figure on it.

#### milestones

| Milestone | Payment
|----------------------|--------
| Completion of app functionality to post to Facebook (example) | $500
| DESCRIBE MILESTONE | PAYMENT

`Guidance` This table variable is where you define the milestones for payment. The "Milestone" column is where the parties describe the services milestone that triggers the ability of the contractor to invoice for the amount in the "Payment" column. It's important to provide as much detail as possible about each milestone. An example might be, "Completion of the wireframe diagrams for the home page, profile page and news feed page."

#### payment period

14 days

`Guidance` Fill this variable in with the amount of time between the customer receiving the invoice and the invoice's due date for payment.

#### payment terms

14 days

`Guidance` This is the amount of time between the customer receiving the invoice and the invoice's due date for payment.

#### rate of payment

$ NUMBER per hour [OR] $ NUMBER per day

`Guidance` This variable can be filled in with: (1) the hourly rate of the contractor; or (2) the daily rate of the contractor.

#### risks to exclude

[PEOPLE AND PROPERTY]

- any death or injury;
- any property damage;

[DIGITAL INDUSTRIES]

- failure of any software, hardware or network components provided by a third party;
- software or hardware that's inaccessible for any reason;
- faulty or lost data associated with the Services;
- digital security issues like software vulnerabilities and malware;
- software in a testing phase like (or analogous to) beta and alpha software;

[CONSULTING]

- reliance on advice communicated by Contractor in whatever form;
- failure to provide correct information or opinions;
- faulty technical advice or data;

[CONSTRUCTION]

- failure of any third party equipment or materials;
- loss connected with access or access problems to the site of work;
- failure to use safety procedures or methods;
- loss during the process of delivery;
- the use, or breakdown of equipment used for the services;

[AGREEMENT RISKS]

- any act or omission connected with the Agreement;
- breaches of the Agreement;
- the termination of the Agreement; or
- any delay in the provision of the Services;

`Guidance` It’s very important to set out the risks that are most likely to cause problems (and get the contractor sued). Don’t rely on the lists in the default text – think of the biggest risks around the services you provide!

#### services description

freelance software development and design services in relation to "[App Name]"

`Guidance` Describe the services provided under the agreement! You need to be specific enough to make clear what the agreement deals with.

#### term duration

for NUMBER days [OR] NUMBER weeks [OR] NUMBER months after the parties enter the Agreement

`Guidance` Fill in the period of time that the agreement will exist between the contractor and the customer. The contractor will provide the services for this period of time, and the customer will need to pay for the services for this period of time.

#### termination process

with 10 days of written notice to the other party

`Guidance` This is how a party can terminate the agreement. The default text sets out a system where you need to warn the other party with a written notification ten days before you terminate the agreement.

#### total amount

$ AMOUNT (including $[*] GST)

`Guidance` Fill in this variable with the total amount that the customer will pay the contractor for the services. It should be an all-inclusive amount because this is the _total_ amount. It’s probably a good idea to set out the amount of GST too.
