# External Calls for Blockchain and DLT
## by Joshua Ellul and Gordon J Pace

It is widely accepted that Blockchain and DLT systems cannot make external calls since all nodes must reach the same deterministic outcome (to reach consensus). However, this does not mean that different nodes cannot undertake different computation - as long as they reach the same deterministic outcome, consensus can be achieved. In this work we proposed that blockchain and DLT systems can make external calls through the use of verifiable signed responses. 

Indeed, this requires that the service being called can provide signed responses back - however, we do not see this to be a problem. The reasons follow: (i) oracles currently required to pay fees to inject information into the chain - using our approch the oracle itself would not have to pay fees (in fact oracles should be paid for such information); and (ii) signed web responses have been proposed to be introduce in web protocols - which we believe will eventually used as a standard.

A pre-print of the paper presenting this approach is available from: <a href="https://www.researchgate.net/publication/351497108" target="_">https://www.researchgate.net/publication/351497108</a>

Geth was modified to demonstrate the approach and serve as a prototype - available from this repo: <a href="https://github.com/joshuaellul/excalls">https://github.com/joshuaellul/excalls</a>
