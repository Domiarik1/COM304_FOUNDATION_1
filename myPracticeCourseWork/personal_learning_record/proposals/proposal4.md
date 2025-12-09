[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [IT Proposals](../proposals/README.md) 

# Council Proposal 4

## Explanation of this proposal
*What do you think this proposal might mean? How might it be implemented?*

Using Raspberry Pi devices as IoT tools for counting people entering and exiting libraries and museums means deploying small, low-cost, network-connected computers to automate football monitoring. These devices use sensors such as infrared beam sensors, ultrasonic sensors, or camera based computer vision to detect when individuals pass through an entry or exit point. Once installed at doorways, the Raspberry Pi reads the sensor data, determines whether someone has gone in or out, and sends this information over a network to a central system for analysis.

The Raspberry Pi acts as the brain of each counting station. It continuously collects data from attached sensors, processes it locally, and communicates the results in real time. Because Raspberry Pi's run a full operating system and support programming languages like Python, they can perform more advanced tasks than basic electronic counters, example, they can filter out false positives, distinguish between directions of movement, store temporary data if the network goes down, and apply basic analytics before sending informations to a server. Using these devices as IoT counters brings several practical benefits. first, they are significantly cheaper than traditional commercial football monitoring systems, making them ideal for public organisations with limited budgets. Libraries and museums often have multiple entrances, so using low-cost devices keeps latge-scale deployment affordable. 

Because the devices are IoT connected, they enable centralised monitoring. This means that all Raspberry Pi counters across multiple branches or buildings can report their data to one unified dashboard. Administrators can see live occupancy levels, compare traffic between locations, and identity patterns such as busy periods, quiet days, or seasonal changes. Using Raspberry Pi's for people counting also requires careful consideration of reliabilty and data privacy. The counting accuracy depends on sensor choice, installation qualify, and environmental conditions. Camera-based systems must comply with privacy laws, often requiring anonymisation or avoidance of storing identifiable images. Regual mainteinace and software unpdates are also needed to ensure the devices remain secure as part of the organisations's network. 

Implementing it involves combining affordable hardware, sensors, and network connectivity to create an automated football-tracking system. Each entance of exit is equipped with a Raspberry Pi and a suitable sensor, such as an infrared break-beam, time-of-flight sensor, or a camera for computer-vision counting. The sensor detects when someone passes through the doorway, and the Raspberry Pi processes this information to determine whether the person is entering or leaving. Institutions can deploy multiple units across different entrances or branches, with all devices reporting automatically. Administrators can then monitor live occupancy, track daily visitor numbers, and analyse peak times. Proper implementation includes ensuring reliable power, secure network configuration, and calibration of sensors. With this setup, libraries and museums gain a low-cost, flexible, and accurate way to track football.


## Technologies and research relevant to this proposal
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*

Session 1 (Getting Started with your Raspberry Pi).

In the past, museums have been places where history and culture are narrated. In recent years, many museum research projects have used tangible systems and mobile applications to replace or augment the traditional museum tour. However, many of these projects provide what are essentially electronic labels rather a new narrative modality. The reason behind people visiting museums is to have declarative learning which means to acquire information that they can speak about. Issues such as social experiences, reflection and connections between cultures, are important parts of the experience. New approaches to help visitors learn and reflect upon these cultural issues in support of museums’ new roles of shaping cultural identify and community building to be explored. This research collaborated with the Baba Nyonya Culture Heritage Museum, Malacca to focus on the Baba Nyonya culture. Because of the cultural diversity of the country, the rich, fusion culture of the Baba Nyonya cuts to the heart of this. 

A pilot museum study was conducted to enhance visitor engagement in cultural learning and reflection by exploring IoT approach to support physical interaction and multisensory experiences. However, the pilot study revealed limited evidence of cultural reflection. In order to improve the result of pilot study, particularly to trigger more reflection, the museum visiting experience was designed as an IoT serious game to include five interactive exhibits -an online trading game, improved Batu Boh and Goldsmith simulators, a new lantern mapping and a virtual house decoration station. The IoT serious game focuses on extending the interactive exhibits to incorporate elements of serious games (games with an educational motivation) to further enhance the visitor experience and encourage cultural reflection using IoT technology. The main museum study design showed how an IoT serious game can be developed with the help of design goals serving as guidelines. The result of the main museum study revealed most participants achieved learning gain to form new understanding of the Peranakan culture and considerably high success in engaging visitors and supporting different levels of reflection. One of the main contributions of the museum studies is the synthesise and translation of design lessons learned as a guideline for future IoT game development. 

The last phase of research involved solving some of the challenges identified in the study, specifically in difficulty with IoT game ideation and establishing communication between IoT sensors and virtual game to allow future museum teams to build similar game experience more easily and effectively. The project introduced an IoT toolkit for future designers to consist of an IoT card game to support game design ideation and IoT development kit as plugin between IoT sensors and the game development platform. The contributions of this thesis are a set of prototype demonstrators, toolkits and guidelines for designing IoT serious game that will aid future developers in designing for cultural learning and reflective experience in museums.

Huang, H., 2020. An IoT approach to bridging virtual and physical reflective learning experiences in museums (Doctoral dissertation, University of Nottingham).

https://eprints.nottingham.ac.uk/60804/


## Initial Analysis of the Proposal
*Use some simple analysis tools to help you think through whether the proposal is a good idea*

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
        <li>idea</li>

       <li>idea</li>
        <li>idea</li>
      </ol> 
    </td>
    <td>
      <ol>
        <li>idea</li>
        <li>idea</li>
        <li>idea</li>
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
        <li>idea</li>
        <li>idea</li>
        <li>idea</li>
      </ol> 
    </td>
    <td>
      <ol>
        <li>idea</li>
        <li>idea</li>
        <li>idea</li>
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
        <li>idea</li>
        <li>idea</li>
        <li>idea</li>
      </ol> 
    </td>
    <td>
      <ol>
        <li>idea</li>
        <li>idea</li>
        <li>idea</li>
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
        <li>idea</li>
        <li>idea</li>
        <li>idea</li>
      </ol> 
    </td>
    <td>
      <ol>
        <li>idea</li>
        <li>idea</li>
        <li>idea</li>
      </ol> 
    </td>
  </tr>
</table> 

## Questions to ask about the proposal
*Without knowing how exactly the council will implement this proposal, what questions should be raised?*

* question 1
* question 2

## Evaluation of the proposal
*Povide a breif evaluation based on what you know*
