[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [IT Proposals](../proposals/README.md) 

# Council Proposal 2

## Explanation of this proposal
*What do you think this proposal might mean? How might it be implemented?*

This outlines a plan to move the software currently hosted in our on-premises server room to a secure, scalable cloud environment. The goal is to improve system performance, reliability, and long-term cost efficiency while supporting the organisations's digital transformation strategy. Cloud platforms provide high availability, automated failover, and built-in redundancy, reducing downtime compared to ageing on-premises hardware.

Cloud providers offer enterprise-grade security, including data encryption, access controls, and continuous monitoring that surpass typical locally hosted environments, moving to the cloud eliminates the need to maintain physical servers, cooling systems, and hardware replacements. The organisation pays only for the resources it uses. Cloud resources can scale up or doen instantly based on demand, supporting business growth without major capital investment.  Cloud-hosted applications are accessible securely from any location, improving flexibility and productivity.


Moving sostware into the cloud involves assessing current systems, choosing a suitable cloud provider, and selecting a migration srategy such as lift-and-shift or modernisation. The cloud environment must be prepared with secure networks, storage, and access controls. Data and applications are then migrated in stages to minimise disruption. Thorough testing ensures performance and security before switching users over. 



## Technologies and research relevant to this proposal
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*

Due to Cloud Computing, the way computing resources are "invented, developed, deployed, scaled, updated, maintained and paid fo" (Marston, Li, Bandyopadhyay, Zhang, & Ghalsasi, 2011, p. 1) is drastically changing (Mell and Grance, 2011). In fact, more and more software and hardware solutions are transferred to Cloud-based technology (EMC, 2016, Pussep et al., 2013). Moreover, the big players of Enterprise Resource Planning (ERP) systems such as Oracle, Sage, SAP, and Microsoft offer their ERP now also in a Cloud-based environment (Chen et al., 2015, Johansson and Ruivo, 2013). This implies not only a change in utilizing computing resources for customers but also a profound shift in the value creation logic of vendors and their partners' business models (Boillat and Legner, 2013, Marston et al., 2011). Hitherto, traditional enterprise software vendors have distributed their software solutions through partners such as Value-Added Resellers (VAR) to their customers (Hedman and Xiao, 2016, Rebsdorf and Hedman, 2014).

The VAR's activities typically include sales, installation, technical consulting, training, modification, and customization of the software at the clients' organization (Sarker et al., 2012). A VAR has personal contact with the end-customers and possesses industry-specific expertise. Thus, the role of the VAR is important for both customer satisfaction and the overall success of the product (Boillat and Legner, 2013). In the past, many enterprise software vendors (e.g. Microsoft, SAP, and Oracle) have introduced partner programs in order to reinforce the relationship to their partners (Hedman and Xiao, 2016).
With service infusion through Cloud Computing, the traditional way of delivering software to the end customers is changing. There is nothing to resell, technically install and there are no opportunities for providing any kind of logistics anymore (Hedman and Xiao, 2016). The delivery of Cloud service is clearly different from the delivery of traditional IT systems, which implies a transition from a goods-dominant logic to a service-dominant logic (Ojala and Tyrväinen, 2011, Vargo and Lusch, 2004).

In relation to this shift, scholars have mainly focused on Cloud Computing technologies adoption, economic benefits of users, the business model evolution of software vendors, and the changing value creation logic through value networks from a rather broad perspective (see e.g. Boillat and Legner, 2013; T. Li et al., 2015, Mohammed et al., 2009, Ojala and Helander, 2014). However, the characteristics of enterprise software such as complexity, high level of dependency, high data volume, and security comprise a special case (Kees, 2015). As on-premise enterprise software rollouts at a client's organization traditionally include several actors in an ecosystem (e.g., VAR and consultancy firms), Cloud Computing seems to disrupt this ecosystem by providing the solution remotely as a service (Ojala and Helander, 2014). Nevertheless, enterprise software solutions still need to solve complex problems and function in a convoluted organization, which cannot be ignored. Conclusively, the value network of Cloud-based enterprise software is not sufficiently investigated.
Little is known about the impact of Cloud Computing on the relationship between enterprise software vendors and business partners as well as about the value creation logic. Although researchers have mentioned the change of the actors' relevance in the value chain of enterprise software, there is no clear answer regarding the future role of those actors (Boillat and Legner, 2013).

(Nieuwenhuis, L.J., Ehrenhard, M.L. and Prause, L., 2018. The shift to Cloud Computing: The impact of disruptive technology on the enterprise software business ecosystem. Technological forecasting and social change, 129, pp.308-313.)

https://www.sciencedirect.com/science/article/abs/pii/S004016251731466X

## Initial Analysis of the Proposal
*Use some simple analysis tools to help you think through whether the proposal is a good idea*

1. Cost Efficiency:

Eliminates the need to purchase and maintain physical servers, networking equipment, cooling, and power.

Moves spending from large up-front capital expenses (CapEx) to flexible operating expenses(OpEx).

Pay-as-yu-go pricing can lower costs for variable workloads.

2 Scalability and Flexibilty:

Easily scale CPU, memory, storage, or instances up or down based on demand.

Great for business experiencing growth, seasonal spikes, or unpredictable usage.

3. Improved Reliability and Uptime:

Cloud providers offer high availability options, redundancy, and disaster recovery built into the platform.

Reduces risk of outages due to hardware failure, cooling issues, or power problems in the server room.

4. Enhanced Security (in most cases)

Major cloud providers invest heavily in security at a scale most organizations cannot match.

Built-in features like encryption, identity management, and logging improve protection.

Compliance certifications (ISO, SOC, HIPAA, etc.) may simplify regulatory requirements.

5. Faster Deployment and Innovation:

Easily deploy new environments, test systems, or services within minutes.

Makes DevOps pipelines easier with infrastructure as code and automation tools.
### SWOT Analysis
*You can use html tables in markdown*
 <table>
  <tr>
    <th>Strength</th>
    <th>Weakness</th>
  </tr>
  <tr>
    <td>
      <ol>
        <li>The cloud allows you to instantly scale computing resources up or down based on demand./li>
        <li>Cloud platforms offer high availability, built-in redundancy, automated backups, and multi-region failover options.</li>
        <li>Cloud providers handle hardware maintenance, updates, security patches, cooling, and power.</li>
      </ol> 
    </td>
    <td>
      <ol>
        <li>Potentially higher long-term costs.</li>
        <li>Dependence on internet connectivity.</li>
        <li>Migration complexity and compatibility issues.</li>
      </ol> 
    </td>
  </tr>
  <tr>
    <th>Opportunity</th>
    <th>Threat</th>
  </tr>
  <tr>
    <td>
      <ol>
        <li>Ability to innovate faster.</li>
        <li>Support for remote and global workforces.</li>
        <li>Enhanced business agility and scalability.</li>
      </ol> 
    </td>
    <td>
      <ol>
        <li>Security breachers or data exposure.</li>
        <li>Vendor lock-in.</li>
        <li>Service outages or provider dependence.</li>
      </ol> 
    </td>
  </tr>
</table> 

### PEST Analysis
*You can use html tables in markdown*

 <table>
  <tr>
    <th>Political</th>
    <th>Economic</th>
  </tr>
  <tr>
    <td>
      <ol>
        <li>Government data protection and privacy regulation.</li>
        <li>International data residency and cross-border policies.</li>
        <li>Government support for digital transformation.</li>
      </ol> 
    </td>
    <td>
      <ol>
        <li>Cost efficiency and reduced capital expenditure (CapEx).</li>
        <li>Scalability reduces financial risk.</li>
        <li>Potential long-term operational costs.</li>
      </ol> 
    </td>
  </tr>
  <tr>
    <th>Social</th>
    <th>Technological</th>
  </tr>
  <tr>
    <td>
      <ol>
        <li>Support for remote and flexible work.</li>
        <li>Collaboration and communication enhancement.</li>
        <li>Skills and training requirements.</li>
      </ol> 
    </td>
    <td>
      <ol>
        <li>Access to advanced technologies.</li>
        <li>Improved infrastructure management.</li>
        <li>Intergration and interoperability.</li>
      </ol> 
    </td>
  </tr>
</table> 

## Questions to ask about the proposal
*Without knowing how exactly the council will implement this proposal, what questions should be raised?*

* question 1
* What are the cost and RIO of moving to the cloud.
* question 2
How will security, compliance, and data privacy be ensured.
## Evaluation of the proposal
*Povide a breif evaluation based on what you know*
Moving software from a server room into the cloud involves migrating applications, data, and services from on-premises physical servers to cloud-based infrastructure managed by a third-party provider. The transition allows organizations to access computing resources over the internet, providing benefits such as scalability, reduced hardware maintenance, improved reliability, and easier remotes access.
