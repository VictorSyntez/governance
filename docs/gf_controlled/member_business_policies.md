# Member Business Policies

This is a Controlled Document of the Canadian Credential Network Governance Framework will be approved by the Canadian Credential Network Board of Directors.

| Document Name | Member Business Policies |
| --- | --- |
| Document Description | This document describes types of Trust Roles and membership available for organizations |
| Version | v0.9 |
| Approval Date | |
| Status | Pre-Launch Phase: Governance Framework Development |
| Governs | Steward Qualification, Application, Activation, Operation, Notification, Suspension, Termination, and Transition |
| Governed By | Canadian Credential Network Governance Framework Work Group |

## 1. Member Qualification
### General
Prospective members MUST apply to the Governing Board and receive approval to be a Member of the Canadian Credential Network. See ```Application ``` process below.

There are several Trust Roles available for organizations: Steward, Registry, Trust Anchor, Issuer.

### Stewards
Prospective members seeking qualification under a membership type that is assigned the responsibility of running a utility infrastructure node MUST be:

1. A business entity that is identifiable with at least one of the following business verification services:
    1. [Verifiable Organizations Network (VON)](https://vonx.io/)
    2. [Legal Entity Identifier Lookup](https://search.gleif.org/#/search/) TBD
    3. *Any other Canadian organization that keep registry of incorporations*
2. A business officially incorporated in Canada for at least three (3) years
3. --

### Trust Anchor

Prospective members seeking qualification under a membership type that is assigned the responsibility of the Trust Anchor MUST be:

1. A business entity that is identifiable with at least one of the following business verification services:
   1. [Verifiable Organizations Network (VON)](https://vonx.io/)
   2. [Legal Entity Identifier Lookup](https://search.gleif.org/#/search/) TBD
2. --
3. --

### Registry

Prospective members seeking qualification under a membership type that is assigned the responsibility of the Registry MUST be:

1. A business entity that is identifiable with at least one of the following business verification services:
   1. [Verifiable Organizations Network (VON)](https://vonx.io/)
   2. [Legal Entity Identifier Lookup](https://search.gleif.org/#/search/) TBD
2. A law firm, accounting firm, or other legally-regulated institution with at least three (3) years operating history.
3. A governmental body or agency, or an entity predominantly owned and controlled by the state, in a Jurisdiction as defined in the [Glossary](../gf_info/glossary.md).
4. --

### Issuer

Prospective members seeking qualification under a membership type that is assigned the responsibility of the Issuer MUST be:

1. A business entity that is identifiable with at least one of the following business verification services:
   1. [Verifiable Organizations Network (VON)](https://vonx.io/)
   2. [Legal Entity Identifier Lookup](https://search.gleif.org/#/search/) TBD
2. --
3. --



<!-- ### Subscribers
Prospective members seeking qualification as a Subscriber MUST be:

1. A corporate or affiliate member of The Linux Foundation.
2. An entity that meets one of the following criteria:

    1. A business entity that is identifiable with at least one of the following business verification services:

        1. [Verifiable Organizations Network (VON)](https://vonx.io/)
        2. [DUNS Number Lookup](https://www.dnb.com/duns-number/lookup.html) TBD
        3. [Legal Entity Identifier Lookup](https://search.gleif.org/#/search/) TBD

    1. A governmental body or agency, or an entity predominantly owned and controlled by the state, in a Jurisdiction as defined in the [Glossary](../gf_info/glossary.md).
    1. A governmentally regulated institution with at least five (5) years operating history.
    1. A law firm, accounting firm, or other legally-regulated institution with at least five (5) years operating history.
    1. A non-governmental organization (NGO) or Social Purpose Organization with at least five (5) years operating history.
    1. An accredited university or other institution of higher education with at least five (5) years operating history.
    1. A certificate authority (CA) with at least five (5) years operating history. -->

## 2. Application Process
<!-- Create Application form -->

### Prospective Member
To apply, an entity MUST submit a written application to the Membership Committee as directed on the Canadian Credential Network website.

### Membership Committee
The committee MUST:

1. Ensure that all specific Practices and Procedures involved in the Member application process are publicly documented on the Canadian Credential Network website.
2. Ensure that Member application process follows the guidelines for Self-Certification, Certification, or Accreditation as specified by the Canadian Credential Network Trust Assurance Framework.
3. Ensure that the application form available upon request and minimally publicly documented on the Canacred-GF source control repo and/or website.
4. Notify applicants of application approval/rejection status.

### Governing Body
The Governing Board MUST:

1. Take action on applications within 30 days of receipt.

## 3. Activation

### Stewards
A Steward SHOULD submit a utility infrastructure node to the Identity Utility Administrator (Authorised Network Administrator) using the procedures outlined by the Technical Steering Committee after the following dependencies have been resolved:

1. Have their application approved by the responsible Canadian Credential Network Governing Body.

Before a Member may qualify to have an active Validator Node on the Utility, the Member MUST:

1. Pass any required tests on the Canadian Credential Network Test Network as specified by the Technical Steering Committee and documented in the Canadian Credential Network Code Repository.

After a Member has qualified to have an active Validator Node, the Member MUST designate the Utility environment(s) (e.g., production, Staging, Development) which their Node may be activated.

1. The Member MUST make this designation following the procedures specified by the Technical Steering Committee.
1. The Member MUST designate activation in at least one Utility environment.
1. The Member MAY designate activation in more than one Utility environment.
1. The Member MUST have at least one node designated for production.

## 4. Operation

1. A Member MUST operate its Node in compliance with the Member Technical and Organizational Policies.
2. A Member MUST requalify at least annually via the requalification process in effect at that point in time as specified by the responsible Canadian Credential Network Governing Body and documented on the Canadian Credential Network website.

## 5. Notification
1. A Member MUST maintain current contact information for its business and technical points of contacts sufficient to ensure its staff are reachable in a timely manner.
2. A Member MUST notify the responsible Canadian Credential Network Governing Body if:

	1. There is a change to the beneficial ownership of its Organization.
	1. There is a change to the Member's legal name, trademark, or logo.
	1. The Member changes the values of any of the Member's attributes submitted in the Member's original application, including legal jurisdiction, legal status, Node location, Node hosting type, or Node technical specifications, that are material to the Node Selection Algorithm.
	1. There is any other substantial change to its Organization that impacts the qualification criteria in the Member Qualification section.
	1. It suffers a data breach or other public event which may reasonably call into question its ability to comply with the Governance Framework.

3. In the case of any of the changes listed in #2 above, the responsible Canadian Credential Network Governing Body MAY require the Member to requalify.
4. The Canadian Credential Network MUST provide Members with at least 30 days notification of any material changes to the business policies implemented in Canadian Credential Network Network environments. Notification about technical changes is covered under Canadian Credential Network Member Technical and Organizational Policies .

## 6. Suspension
1. A Member MUST be suspended by the responsible Canadian Credential Network Governing Body under any of the following conditions:

  1. The Member no longer complies with the Member Business Policies, Member Technical and Organizational Policies, or any other requirements of the Canadian Credential Network Governance Framework.
	1. The Member's Node has failed to achieve 98% availability over a period of 30 days.
	1. A security intrusion or violation has been reported and the Technical Steering Committee is not satisfied that the Member has performed adequate remediation.
	1. The Member fails to requalify under its annual requalification process specified in section 4.
	1. The Member has, in the sole judgment of the Canadian Credential Network Board of Directors, violated some or all of the Governance Framework principles, taken action against the purpose of the Canadian Credential Network, or has shown behavior contrary to the collective interest of the Canadian Credential Network or performed action that brought the Canadian Credential Network or the Consortium into disrepute.

2. A Member who is suspended MUST not have an active Node on any Canadian Credential Network Ledger network until such time as Member is able to provide reasonable assurance to the responsible Canadian Credential Network Governing Body that:

	1. The Member is back in compliance with all requirements of the Canadian Credential Network Governance Framework, and
	1. The Member has the ability to maintain compliance for the foreseeable future.

3. At the request of a suspended Member, the responsible Canadian Credential Network Governing Body MUST examine the Member's remediation efforts and make one of the following decisions:

	1. Reactivate the Member.
	1. Request further remediation by the Member.
	1. Terminate the Member.

## 7. Termination
1. A Member who has breached the terms of the Participant Agreement and/or associated Utility Agreements MAY be
terminated by a majority vote of the responsible Canadian Credential Network Governing Body with ratification by the Board of Directors.
2. A Member who has been suspended and not been reactivated within 180 days following suspension MUST be notified of automatic termination.
3. An Organization who has been previously terminated as a Member and who applies to be reinstated MUST disclose the previous termination in their application and explain the remediation steps that the Member has taken to requalify.
