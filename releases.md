---
layout: default
---

# Key4HEP Packages & Releases

Key4HEP provides a consistent stack of its projects together with some of its experiment-specific client packages.

## Releases

Add here a list of releases and how to set them up

## General Packages

{:class="table table-striped"}
Package | Homepage | Description
-----         | -----     | -----
 edm4hep | <https://github.com/key4hep/EDM4hep> |     Common event data model
 k4actstracking |    <https://github.com/key4hep/k4ActsTracking>    |     Acts tracking components
 k4fwcore | <https://github.com/key4hep/k4FWCore> |     Core framework components
 k4gen | <https://github.com/HEP-FCC/k4Gen/> |     Generator components
 k4pandora | <https://github.com/key4hep/k4Pandora> |     Pandora app for Key4HEP
 k4projecttemplate | <https://github.com/key4hep/k4-project-template/> |     Template for Key4hep framework projects
 k4reccalorimeter | <https://github.com/HEP-FCC/k4RecCalorimeter/> |     Calorimeter reconstruction components
 k4simgeant4 | <https://github.com/HEP-FCC/k4SimGeant4/> |     Geant4 components
 podio | <https://github.com/AIDASoft/podio> |     PODIO, or plain-old-data I/O, is a C++ library to support the creation    and handling of data models in particle physics.
  key4hep-stack | <https://cern.ch/key4hep> |     Bundle package to install the Key4hep software stack.
 k4lcioreader | <https://github.com/key4hep/k4LCIOReader> |     LCIO reader based on PODIO and EDM4hep
 k4marlinwrapper | <https://github.com/key4hep/k4MarlinWrapper> |     Gaudify Marlin Processors in order to run them in the Key4HEP framework


## Experiment specific packages

Several experiment specific packages are currently being transformed to be more generic or which could be if there is interest from outside. Please find below a list of these packages.


### FCC

{:class="table table-striped"}
Package | Homepage | Description
-----         | -----     | -----
 fcc-edm | <https://github.com/HEP-FCC/fcc-edm> |     Event data model of FCC
 fccanalyses | <https://github.com/HEP-FCC/FCCAnalyses> |      RDF Analysers for the FCC.
 fccdetectors | <https://github.com/HEP-FCC/FCCDetectors/> |     FCC Detector Descriptions
 fccsw | <https://github.com/HEP-FCC/FCCSW/> |     Software framework of the FCC project
 dual-readout | <https://github.com/HEP-FCC/dual-readout> |     Repository for GEANT4 simulation & analysis of the dual-readout    calorimeter

### ILC / CLIC

{:class="table table-striped"}
Package | Homepage | Description
-----         | -----     | -----
 aidatt | <https://github.com/AIDASoft/aidaTT> |     Tracking toolkit developed in the AIDA project.
 ced | <https://github.com/iLCSoft/CED> |     CED is a server client application for OpenGL drawing
 cedviewer | <https://github.com/iLCSoft/CEDViewer> |     CEDViewer processor for the CED event display.
 conformaltracking | <https://github.com/iLCSoft/ConformalTracking/> | Package for running pattern recognition based o conformal mapping and    cellular automaton. This is not tied to a given geometry, but has been    developed for the CLIC detector model 2015.
 ilcsoft | <https://cern.ch/key4hep> |     Bundle package to install Ilcsoft
 ilcutil | <https://github.com/iLCSoft/ilcutil> |      A utility package for the iLCSoft software framework
 ildperformance | <https://github.com/iLCSoft/ILDPerformance> |     Assembly of various Marlin processor for reconstruction.
 marlin | <https://github.com/iLCSoft/marlin> |      Linear Collider framework
 marlindd4hep | <https://github.com/iLCSoft/MarlinDD4hep> |     Provides one processor to initialize a DD4hep detector geometry from a    compact file for a Marlin job.
 marlinfastjet | <https://github.com/iLCSoft/MarlinFastjet> |     Marlin processor to interface FastJet.
 marlinkinfit | <https://github.com/iLCSoft/MarlinKinfit> |     Kinematic Fitting Library for Marlin
 marlinkinfitprocessors | <https://github.com/iLCSoft/MarlinKinfitProcessors> |     A collection of Marlin processors that use the MarlinKinFit package
 marlinpandora | <https://github.com/PandoraPFA/MarlinPandora> |     Pandora App for Marlin.
 marlinreco | <https://github.com/iLCSoft/MarlinReco> |     Assembly of various Marlin processor for reconstruction.
 marlintrkprocessors | <https://github.com/iLCSoft/MarlinTrkProcessors> |     A collection of Tracking Relelated Processors Based on MarlinTrk
 marlinutil | <https://github.com/iLCSoft/MarlinUtil/> |      Library that contains classes and functions that are used by more than    one processor. In particular it contains the geometry classes that are used until we have the geometry for reconstruction package (GEAR).
 clicperformance | <https://github.com/iLCSoft/ClicPerformance> |      Package containing processors and configurations to determine the    performance of the CLIC detector model
 clupatra | <https://github.com/iLCSoft/Clupatra> |     Topological pattern recognition (for the TPC)
 conddbmysql | <https://github.com/iLCSoft/conddbmysql> |      Linear Collider MySQL Conditions Database
 ddkaltest | <https://github.com/iLCSoft/DDKalTest> |     Interface between KalTest fitter and DD4hep based geometry
 ddmarlinpandora | <https://github.com/iLCSoft/DDMarlinPandora/archive/v00-11.tar.gz> |     Interface between Marlin and PandoraPFA.
 fcalclusterer | <https://github.com/FCalSW/FCalClusterer> |     Reconstruction for the Forward Calorimeters of Future e+e- colliders.
 forwardtracking | <https://github.com/iLCSoft/ForwardTracking> |     Track Reconstruction for the Forward Direction (for the FTD)
 garlic | <https://github.com/iLCSoft/Garlic> |     Garlic is a Marlin Processor to identify photons and electrons.
 gear | <https://github.com/iLCSoft/gear> |      Linear Collider Conditions Data toolkit.
 kaldet | <https://github.com/iLCSoft/KalDet> |     Kaldet: part of ilcsoft tracking.
 kaltest | <https://github.com/iLCSoft/KalTest> |      Kaltest tracking software.
 kitrack | <https://github.com/iLCSoft/KiTrack> |     Toolkit for Tracking. Consists of KiTrack (Cellular Automaton, a    Hopfield Neural Network, the hit and track classes) and Criteria (the    criteria classes).
 kitrackmarlin | <https://github.com/iLCSoft/KiTrackMarlin> |     Implementation of classes for the use of KiTrack by Marlin
 lccd | <https://github.com/iLCSoft/lccd> |      Linear Collider Conditions Data toolkit.
 lcfiplus | <https://github.com/lcfiplus/LCFIPlus> |     Flavor tagging code for ILC detectors, for documentation consult    confluence at https://confluence.slac.stanford.edu/display/ilc/LCFIPlus
 lcfivertex | <https://github.com/iLCSoft/LCFIVertex> |     Package for vertex finding as well as vertex charge determination in b-    and c-jets.
 lcgeo | <https://github.com/iLCSoft/lcgeo> |     DD4hep geometry models for future colliders.
 lctuple | <https://github.com/iLCSoft/LCTuple> |     Marlin package that creates a ROOT TTree with a column wise ntuple from    LCIO collections.
 overlay | <https://github.com/iLCSoft/Overlay> |     The package Overlay provides code for event overlay with Marlin.
 raida | <https://github.com/iLCSoft/raida> |      A utility package for the iLCSoft software framework

### CEPC

{:class="table table-striped"}
Package | Homepage | Description
-----         | -----     | -----
 cepcsw | <https://github.com/cepc/CEPCSW> |     CEPC offline experiment software based on Key4hep.


 