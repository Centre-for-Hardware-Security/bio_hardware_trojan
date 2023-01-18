#  A Pragmatic Methodology for Blind Hardware Trojan Insertion in Finalized Layouts

  IEEE/ACM International Conference on Computer-Aided Design (ICCAD) 2022
  
  Authors: A. Hepp*, T. Perez+, S. Pagliarini+, G. Sigl*
  
\*Technical University of Munich

\+Tallinn University of Techonology

#

# Description:

This repository contains additional results from the published paper. In total, 96 modified layouts utilizing the BioHT tool

#
#    Abstract:

 A potential vulnerability for integrated circuits (ICs) is the insertion of
 hardware trojans (HTs) during manufacturing. Understanding the practicability
 of such an attack can lead to appropriate measures for mitigating it. In this
 paper, we demonstrate a pragmatic framework for analyzing HT susceptibility of
 finalized layouts. Our framework is representative of a fabrication-time
 attack, where the adversary is assumed to have access only to a layout
 representation of the circuit. The framework inserts trojans into
 tapeout-ready layouts utilizing an Engineering Change Order (ECO) flow.
 The attacked security nodes are blindly searched utilizing reverse-engineering
 techniques. For our experimental investigation, we utilized three crypto-cores
 (AES-128, SHA-256, and RSA) and a microcontroller (RISC-V) as targets.
 We explored 96 combinations of triggers, payloads and targets for our
 framework. Our findings demonstrate that even in high-density designs, the
 covert insertion of sophisticated trojans is possible. All this while
 maintaining the original target logic, with minimal impact on power and
 performance. Furthermore, from our exploration, we conclude that it is too
 naive to only utilize placement resources as a metric for HT vulnerability.
 This work highlights that the HT insertion success is a complex function of
 the placement, routing resources, the position of the attacked nodes, and
 further design-specific characteristics. As a result, our framework goes
 beyond just an attack, we present the most advanced analysis tool to assess
 the vulnerability of HT insertion into finalized layouts.

#

