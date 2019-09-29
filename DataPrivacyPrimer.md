## Data privacy - Standards, Regulations across world & India

- [Concepts & Principles](#concepts---principles)
  * [What is Data Privacy & Need ?](#what-is-data-privacy---need--)
  * [How is Data Privacy different from Data Security ?](#how-is-data-privacy-different-from-data-security--)
  * [Theory of "Privacy by Design"](#theory-of--privacy-by-design-)
- [Regulation](#regulation)
  * [Background](#background)
  * [Key Definitions](#key-definitions)
  * [Scope](#scope)
  * [Obligations of Data Protection](#obligations-of-data-protection)
  * [Grounds for processing Personal Data](#grounds-for-processing-personal-data)
  * [Data Principal Rights](#data-principal-rights)
  * [Transparency & Accountability Measures](#transparency---accountability-measures)
  * [Transfer of Personal Data outside Territory](#transfer-of-personal-data-outside-territory)
  * [Exemptions](#exemptions)
  * [Supervisory authorities -  Data Protection authority of India](#supervisory-authorities----data-protection-authority-of-india)
  * [Penalities and Remedies](#penalities-and-remedies)
  * [Appellatte Tribunal](#appellatte-tribunal)
  * [Timelines](#timelines)

## Concepts & Principles
### What is Data Privacy & Need ?
Data Privacy as a concept often deals with the way how the data of the customers/partners is handled by the organizations i.e. How & what is collected, stored, consented, used, shared further & disposed. (Life cycle of the Data)  

Data has become an important asset for any companies to do a range of things. Some of the them, but not limiting to these include providing personalized services, targeted advertisements, recommendation systems, predicting sales/revenues/growth, observing shifts in behaviors & even predicting/influencing democratic processes like elections, as we have seen in news recently.  The recent advancement in information technologies like Data mining & Machine learning has even more emphasized the need for every organization to have large & varied feature sets of data about its customers.  

As more & more organizations realizing the importance of data & started collecting it; without a proper guiding & regulatory framework in place, there is a great risk of data being heavily misused.  Data Privacy focuses on such framework & guidelines that can help statutory bodies frame efficient policies to help curtail the misuse & promote a responsible usage. 
 
### How is Data Privacy different from Data Security ?
Often we see people interchangeably use the terms "Data Privacy" & "Data Security", however there is a subtle difference between the two terms. "Data Security" often deals with protecting the data from adversaries/unauthorized personnel & is achieved through a mix of security controls & practices like White listing, controlling the data access workflows,  logging, authentication, encryption (storage & transit), resilient system design, backups etc.  On the other hand Data Privacy deals with the complete life cycle of the data all the way from consent, collection, storage, processing, sharing & disposal.  Data Security/Information Security is generally seen as a sub part of the broader subject of "Data Privacy"

For example, An organization collecting personal data of its customers has implemented all the necessary controls & processes to ensure the data collection, processing & storage is protected from unauthorized personnel but didn't take the necessary consent from its customers on what data is being collected & howz it processed/shared with others; then such an organization can be seen as achieving Data Security, but not the Data privacy.

Data Security can exist without Data Privacy, but the reverse is not possible. Data privacy cannot be achieved without Data security.

### Theory of "Privacy by Design"
"Privacy by Design" (PbD) is a set of 7 broader principles that provide guidance for achieving privacy in any system or workflow without limiting it to Information Technology. Initially proposed by Ann Cavoukian (Information & Privacy commissioner, Ontario) 20 years back as a set of guidelines, has now become the basis for many systems & regulations including EU's GDPR.

1. **Proactive not Reactive; Preventative not Remedial**
This principle emphasizes on anticipating privacy risks in the product/service/workflow ahead of time rather than trying to fix after the fact i.e. after a privacy breach.  It expects the planning process to assess the privacy risks involved & take proactive measures.   
 
2. **Privacy as the Default Setting**
Privacy of the consumer/subject should be the default option of the system in any case & should not be a voluntary Opt-in or shouldn't require any explicit action to be done by consumer to enable privacy.   *"Maximum privacy protection"* should be offered as a baseline & this is where most of the today's social networking system might not really fall in place  & trying to keep up.  xref'ed an [example](https://www.forbes.com/sites/larrymagid/2014/05/22/facebook-changes-default-privacy-setting-for-new-users/#6b5f921a59ac) to help understand this better.  *"Data minimization"* - Collecting only the data absolutely needed, *"Restricted sharing"* - Sharing only the minimum required data with processing systems, *"Only agreed Retention Periods"* are few others steps generally taken in this direction.  
 
3. **Privacy Embedded into Design**
This principle emphasizes on designing IT systems with privacy as a core feature/function, rather than as a patch work on the top of the functional product, which is often the case.  Introducing security & privacy after a fully functional system design is going to be counter productive, costly & most of the times is ineffective.  For example, Systems that provide *"least & appropriate privilege access"* to the parties involved at different stages of the workflow, *"Access logging"*,  *"Secure coding practices adaption"* , *"Sound patching policy frameworks"* are few steps that generally fall under this principle.  

4. **Full Functionality - Positive-Sum, Not Zero-Sum**
PbD shouldn't impair the system from its Functionality i.e. it shouldn't be a tradeoff between privacy & Full functionality.  Privacy should also be treated as a clear functionality requirement & should be equally met along with other functional features

5. **End-to-End Security - Lifecycle Protection**
This principle emphasizes on responsibility of protecting the privacy of the data through its entire Life cycle. right from when it enters the system, travels subsystems/3rd party systems, processed, archived & until it is destroyed.  Privacy should be protected all the way, even if the data crosses the organizational & geographical boundaries. 
As xref'ed [here](https://www.computerworld.com/article/2531776/a-real-dumpster-dive--bank-tosses-personal-data--checks.html), we often see mutliple organizations dont really dispose information well after use, resulting in privacy breaches & no providing protection through the entire life cycle.

6. **Visibility and Transparency**
Emphasizes on stakeholders/consumers to have visibility into what data being collected, how it is being secured on premises, what it is used for, who is accountable, to whom the data being further transferred, for what purposes, howz the data being securely transmitted, how long its been retained, how it is archived & destroyed etc..  Having visibility into such above information can help build trust among the consumers. Providing accountability for protecting the data collected, openness & transparency in the data being collected, practices being followed through out the life cycle, Compliance management through 3rd party auditing systems are few steps that generally fall under this principle.

7. **Respect for User Privacy**
Above all, PbD suggests to put the Users Interests at the top most priority for any body dealing with the system, be it operators, developers/architects & recommends the system to be user-centric.  Recommends the systems should empower the subject/consumer to play an active role in the management of their own data.   Taking proper consent, providing accurate details on the data being collected for the purpose, Providing access to individuals data stored/shared with 3rd parties at any point of time, Ability for an individual to delete Data across systems (including 3rd parties), Providing redress mechanisms are some steps that fall under this principle.
Ability to [download the data from our Google](https://support.google.com/accounts/answer/3024190?hl=en) account can be seen as a step to adopt this principle. 

## Regulation
Under this section we will try to discuss the key provisions of the  newly proposed India's Data protection Bill - 2018 in comparison with the European Union's (GDPR) [General Data Protection regulation](https://gdpr-info.eu) which came into force in May 2018 after being adopted in 2016 (Giving essentially 2 years of period for organizations to comply)

### Background
Currently In India, the data provided by Individuals to the organizations/body corporate is governed under the rules [Reasonable Security practices and procedures and sensitive personal data or Information](https://www.wipo.int/edocs/lexdocs/laws/en/in/in098en.pdf), made through an official Gazette notification. 

Though the rules exercise some regulation on the body corporate (organizations) that collect data, they clearly fall short on enforcing all the principles of "Privacy by Design". For example *no requirements of explicit consent seeking*, *no provisions for individual to manage his own data*, *no provisions to enforce transparency & visibility*, "law limiting to body corporate & not individuals" etc..  

Following a petition challenging the constitutional validity of the aadhar on the grounds of violating the right to privacy, Supreme court held that "Right to Privacy" is an intrinsic part of fundamental right of "right to life & personal liberty" under article 21.  Under the chairmanship of Justice B.N. Srikrishna, a committee was setup to review (i) various issues related to data protection in india (ii) recommend methods to address them and (iii) propose a draft [Personal data protection bill](https://meity.gov.in/writereaddata/files/Personal_Data_Protection_Bill,2018.pdf) which was presented to MeitY in 2018.

Most of the provisions in this bill can be seen as borrowed from the GDPR, which by the time has established itself as the most comprehensive Data protection law ever.

### Key Definitions

**Personal Data** The definition of *Personal data* generally varies from one regulation to other. However there is close resemblance in the way personal data is defined in both EU's GDPR & the Personal Data protection Bill- 2018 of India.  Both are almost one & the same except the language changes. Here is the snippet from the India's bill.
```
"Personal data" means data about or relating to a natural person who is directly or indirectly
 identifiable, having regard to any characteristic, trait, attribute or any other feature of the
 identity of such natural person,or any combination of such features, or any combination of such
 features with any other information;
```
So, the above definition clearly says that any info that can identify a natural living person is Personal Data. That's the reason even the website cookies (which generally identify the end user) that are stored by the webservers is treated as personal data & websites started asking your consent in the recent times (post GDPR regulation). 

While the overall general definition of the Personal data remains same with India & EU, there are some minute differences over some special categories. GDPR defines few special categories of personal data which it specifies to be protected with additional measures that include explicit consent & good reason. Few such categories are

-   racial or ethnic origin,
-   political opinions,
-   religious or philosophical beliefs,
-   trade union membership,
-   genetic data, biometric data,
-   health data,
-   sex life and sexual orientation.

For such special categories, India's Data protection bill mentioned a seperate term called **Sensitive Personal Data**  & included some more data items like Passwords, official identifiers, financial data, religious belief etc which are not in special categories in GDPR.

**Data Principal  / Data Subject (GDPR)** Person whose data is being collected is referred to as Data Principal in the Bill. Same is called Data Subject in GDPR

**Data Fiduciary / Controller (GDPR)** Any person/company/state/juristic entry who alone on in combination with others defines the Purpose & means of processing the personal data.  Logically to whom we as a Data principal will be handing over our data. 

**Data processor / Processor (GDPR)** Any person/company/state/juristic entry who processes the personal data on behalf of Data fiduciary, but does not include an employee of fiduciary.

**Profiling** Any form of processing of personal data that analyses or predicts aspects concerning the behaviour, attributes or interest of a data principal.

**De-identification / Pseudonymisation (GDPR)** Redacting/Masking of the parts of data by fiduciary or processor, such that the data cannot be attributed to a principal.

### Scope
Act applies to the parties in the below scenarios.
(i) if the data is either collected/disclosed/shared/processed with in the territory of India
(ii) Other bodies (including state) incorporated under the Indian Law - Covering the comanies registered under Comapnies act, operating in foreign territory over Indian Data.
(iii) Foriegn Data fiduciaries that are in connecting with any business carried in India or directly offering goods/services to the principals in India - Essentially covers all foriegn operated Websites that has Indian data principals.

Act shall not apply to processing of anonymized data, where certain data point/feature or a combination cannot be used to identify a particular principal.

Essentially the scope is exactly same as GDPR.

### Obligations of Data Protection
In chapter 2 of the act, the Draft bill defines few obligations of the fiduciaries & processors. Some of the imp ones include
**Fair and reasonable Processing** any person processing the personal data owes a duty to the data principal to process such data in fair & reasonable manner that respects the privacy of data principal.  However there dont seem to be any guidelines that define what a "Fair & reasonable processing" is & legal experts believe that without such guideline, such fairness can vary from one fiduciary to other.
**Purpose Limitation & Collection Limitation**  One of the key obligations is that the fiduciary/processor is limited to process/collect just the necessary data only required for the purpose specified & cannot be used for anything else.
**Notice** Mandates the fiduciary to provide following information at the time of data collection. very few of the key items include 
i.) purpose ii) category of personal data being collected iii) identity & contact details of fiduciary iv) right of the principal to withdraw consent & procedure for the same v) info of fiduciaries & processors to whom the data may be shared vi) **the source of such collection, if the personal data is not collected from the principal** vii) data retention periods viii) greviance redressal procedure 

The reason i highlighted the 6th one is after the enactment of this bill, Telecallers who eat your phone battery with 10 calls a day are mandated to share the source of their info. :) 

**Data Quality** fiduciary is mandated to take reasonable steps to ensure that personal data processed is complete, accurate, not misleading and updated, while it is processed, handed over to processors etc.

Now, This is a key provision to hold the government officials accountable who often have quality issues with the data they maintain :)

**Data Retention**  Hold data only just as long as it is needed for the purpose unless explicitly mandated otherwise. Should do frequent reviews of the data in procession.

**Acccountability** Fiduciary is made responsible for the obligations set out in the act, even if  the processing is undertaken by 3rd party on its behalf & should be able to demonstrate the same. 

### Grounds for processing Personal Data
While there are provisions to process the personal data through consent of the Principal, there are other provisions that dont require consent that include 
i.) Processing of sensitive personal data for certain functions of the State  -- Guess this definitely covers some parts of Aadhaar & gives some backing; 
ii.) Processing of sensitive personal data in compliance with law or any order of any court or tribunal
iii.) Processing of certain categories of sensitive personal data for prompt action (in situations of Medical emergency, Disasters, breakdown of public order etc.)

Don't see such separate sections providing exemptions for Govt's in GDPR, though it gave space for the member countries to adjust & adopt the "lawfulness of processing" section accordingly.

A separate section is called out for the personal data processing of the children & restricts fiduciaries from profiling & tracking the for the targeted advertisement of the children that can cause significant harm to the child. 

### Data Principal Rights
**Right to confirmation and access**  Fiduciary is mandated to provide the principal with the data being processed, how it is processed, what it is processed for & whether the processing is still on going or complete.

**Right to Correction** Principals ability to access the data being processed, correct any inappropriate/misleading/outdated information.  Failing to provide such option for correction, fiduciary should give reasonable justification.

Now our govt offices cant tell bluntly that this can't be corrected without a reason. Hope :)

**Right to Data portability** Right to receive the personal data from the fiduciary in a commonly used/structured format consumable by other systems. Obviously the law enforcement agencies are barred under compliance with Law.

**Right to be Forgotten** Right of the data principal to restrict or prevent continuing disclousure of personal data by fiduciary in case of (i) data is no longer needed by fiduciary (ii) consent withdrawn (iii) was contarary to any other state law.

*Though the head section says it as **"Right to be forgotten"**, the description of the provision asks for restriction/prevention of processing/disclosure, but dont explicitly talk about erasing the data. unlike India's bill, GDPR speaks clearly in this case; As per GDPR **"Right to Restriction" ,"Right to be forgotten" are two different things**, where restriction is seen as a temporary/permanent restriction on the fiduciary to process the data, but fiduciary is allowed to store data. Erasure speaks of complete erasure of data across the replciated & shared copies.*   

In any case, explicitly defining the rights of Data principal is a great step in providing control over individuals own data, which was clearly missing in the existing gazette rules.

### Transparency & Accountability Measures
Recommends adopting the concepts of PbD. Fiduciary is held responsible for taking steps to maintain transparency regarding its general practices & make info available for principal as discussed in the Obligation section.  Mandates the Fiduciary, processors to adopt reasonable safeguards to protect the data from misuse/unauthorized access. 

**Incase of a Personal Data breach** Fiduciary is made responsible to report to authority immediately/within the time specified, incase of any personal data breach, only when such breach is likely to cause harm to any data principal, while its working on containing/responding to breach.  This provision of reporting only when such breach has potential to harm the principal is again subjective to interpretation of fiduciary without proper guidelines in place.  There is no reasoning as such on why not report every data breach to authority.  

As the Authority is vested with responsibilities of monitoring the fiduciaries to protect the interests of principal & has powers to summon fiduciaries for not following the provisions of the act, there is inherent conflict of Interest & fiduciaries may try to avoid reporting breaches, until there is a clear guideline to interpret the harm caused to principal by the data breach. 

Upon receiving such notification of a Data breach, Authority upon assessing the harm caused to the data principal, may direct the fiduciary to disclose the situation to the principal (may not as well) & authority has powers to seek additional information from the principal, if it is needed to protect the interests of the principal.

In a slight deviation to India's bill, GDPR calls for the notification of the breach to subject by Authority unless the controller took corrective measures.

**Data protection Impact Assessment** Whenever a data fiduciary is taking up a project of data processing involving new technologies that profile large amounts of sensitive personal data, such processing shall not be commenced until a Data protection impact assessment has been carried out by the DPO (Data protection officer) & is submitted to Authority. Authority has powers to define, on what processes the DPI should be carried out & where the authority should himself involve in the process of DPI assessment.

**Record Keeping & Audits** Certain fiduciaries (upon notified by authority) is made responsible to maintain records of the info that tells about how the data operations are carried out, DPI reports, periodic review reports & any other processing changes be recorded for the Audit purposes. An annual audit by Independent data auditor is mandated under this act.

**Data Protection Officer** Certain data fiduciary (upon notified by authority) shall appoint a DPO to advice on matters relating to the fulfilling of the obligations of the act,  monitor the data processing activities & advice of change in the processes accordingly, engage & communicate with authority, record keeping of the processing activities, act as a POC for grievance reporting.  Foriegn companies operating on the data of Indian principals, are mandated to appoint a DPO based out of India.

**Restrictions on processors** The bill restricts the Data processors from further engaging another data processors without the consent/authorization of the fiduciary.

GDPR has been more clear on the restrictions of the processors. One of the important provisions include , Processors obligated to assist the controller (fiduciary in Indian context) with all the required info for the controller to meet the compliance requirements. Other provisions include documented instructions of processing as a pre-req for any new type of data processing.

**Significant Data fiduciaries** A section of data fiduciaries matching certain criteria as prescribed by authority will be classified as Significant Data fiduciaries (generally based on the type, volumes of data & the impact of breach).  Such significant data fiduciaries are mandated on the above obligations like DPIA, Record keeping & Audits on all types of data processing they carry out.

**Grievance Redressal** Every data fiduciary is mandated to have a grievance redressal mechanism & proper procedures in place to address them as they come in. Data principal can raise a grievance with the DPO/any other officer designated (incase of a non-significant DF) if the fiduciary is found to be violating any of the provisions of the act. The bill mandates to resolve any such grievances with prirority & prescribed a maximum timeline for resolution as 30 days, post which the Principal can take the matter to an adjudicating offiicer.

### Transfer of Personal Data outside Territory
Data fiduciaries are mandated to maintain at-least a single copy of the data being sent out to a foreign country for processing & that too after meeting the conditions of Corss border transfer.  There are provisions for Central govt to notify some type of data as "Critical personal Data" which is not allowed to be processed outside the territory at any case. At the same time govt has provisions to exempt certain data from the above mandated restrictions, but cannot exempt sensitive personal data. 

Unlike India's draft bill, GDPR allows for transfer of the data to foreign country provided the Controllers & processors meet the stipulated requirements of safeguards & compliance as mentioned in the Act.

Enterprises might not be very happy with this provision, given the cost associated in maintaining additional copies of the data locally & can also amount to the scaling problems with the Infrastructure we have in India. Cloud services like AWS though have decent presense, a lot of the native features/services are not available for AWS Mumbai.

### Exemptions
Allows state machinery to process the personal data in the interest of state security, provided such processing is backed by a procedure established by law. (written in negative context section 43, subsection 1)
Allows for disclosure of personal data for enforcing any legal right or claim, for any other judicial function, for research, archiving, Journalisitic, domestic purposes & is exempted from the obligations.

Another interesting provision here is that the small entities that does manual processing of the data, where they dont have infrastructure to automate the processing are exempted from few obligations like Notice, Data quality & retention.   Any entity that dont have a turn over of 20 lakhs/year or above is considered a Small entity 

### Supervisory authorities -  Data Protection authority of India
The Bill calls for an establishment of an independent statutory authority  called "Data Protection Authority of India" which has powers to hold & dispose properties (both movable & immovable) subject to the provisions of the act.

Composition :- A chairperson & 6 whole time members. Appointment is made by central govt on the recommendations of committee comprising
- CJI or an SC judge nominated by CJI (Chairperson of the committee)
- Cabinet Secretary 
- One domain expert to be nominated by CJI or SC judge (nominated by CJI)

**Security of Tenure** is the key for any statutory body to execute the authority independently. Though the bill is not proposing for the authority to be constitutionally backed, it has provisions to restrict the central government from modifying the salaries to the disadvantage (once prescribed) during the term.  There are also clear guidelines mentioned on when a member/chairperson can be removed by Central govt, providing some sort of Independence to the authority.

GDPR being a common regulation for the  union refrains from defining any such minute details of security of tenure of supervisory org, but directivises member states to establish a similar Independent authority;

**Powers & Functions of Authority** Its the duty of authority to protect the interests of data principals, prevent any misuse of personal data, ensure compliance with the provisions of this Act, and promote awareness of data protection. With a documented list of powers, authority in general also have rights to issue directions to fiduciaries & processors time to time after hearing from the fiduciaries & processors. It has the powers to call for any information from any fiduciary or operator required for it to discharge its functions. Has powers to conduct inquiry once it has some reasonable ground to believe that the procedures/activities of the parties involved are determinant to the interests of the principal.

### Penalities and Remedies
While the GDPR only talks about remedies & compensation to the victim, India's PDP Bill -2018, along with compensation goes ahead & prescribes penalities for fiduciaries & operators that fail to comply. The funds collected through penalties are credited to "Data Protection Awareness Funds" which shall be used by DPA to discharge its function of raising data privacy awareness among the public.

There will be a separate adjudication wing in the DPA to hear the appeals by the Principals against the DPO's/ Fiduciaries. Appointment, Jurisdiction, security of tenure of such a wing is to be decided by Central government. This again calls for the conflict of interest between adjudication wing & State machinery.

### Appellatte Tribunal
Central govt by notification will establish an Appellatte tribunal to hear over the appeals on the rewards of the adjudication wing & the conditions of service are protected from disadvantage by central govt. Civil courts will not have any jurisdiction on the matters where the Appallate tribunal is empowered to jurisdicate.

### Timelines
The bill calls for a notified date (notified date should be less than 12 months from the day act is passed) to be published, post date with in 3 months DPA has to be setup. DPA after establishing, within 12 months from the notified date has to issue codes of practice defined in the above sections. The total act will come into force after 18 months of the notified date.

While there are still some issues to sort out, DPR Bill - 2018 is a great step for India to protect its subjects interests. There are definitely issues that overkill businesses, which needs to be sorted out through Industry consultations before the act is passed.  Nevertheless GDPR has established a great standard for other countries to follow & Improvise on.

Hoping for a better Data protection regulation that protects the interests of principals, at the same time dont compromise the interests of businesses & states alike.