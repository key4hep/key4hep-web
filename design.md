---
layout: default
---
# Key4HEP design principles

The basic philosophy of Key4HEP is to provide an out-of-the-box solution for experiment data processing, built from loosely coupled, but consistenly defined software products. An integral part of the design is a separation of data and algorithms. While the data layout is based on EDM4HEP, algorithms and their scheduling is managed by Gaudi.

The Kep4HEP stack is organised in layers:

<div class="alert alert-dismissible alert-success">
  <h4 class="alert-heading">4. User Layer</h4>
  Experiment Software Using Key4HEP. Some of this software may become part of Key4Hep in the future
</div>
<div class="alert alert-dismissible alert-info">
  <h4 class="alert-heading">3. Top Layer</h4>
  Projects using EDM4Hep and Gaudi as common 'protocols' to interoperate and exchange data with each other. This is where Key4HEP ensures consistency and ease-of-use. 
</div>
<div class="alert alert-dismissible alert-primary">
  <h4 class="alert-heading">2. "Protocol" Layer</h4>
  The middle layer is mainly defined by a common event-data model (EDM4HEP), and a common data processing framework (Gaudi).
</div>
<div class="alert alert-dismissible alert-danger">
  <h4 class="alert-heading">1. Foundation Layer</h4>
  The first Key4HEP layer covers persistency libraries, geometry handling, conditions data, generic tracking, and similar. The libraries at this layer are largely independent from each other.
</div>
<div class="alert alert-dismissible alert-warning">
  <h4 class="alert-heading">0. External Libraries</h4>
  The bottom most layer consists of libraries and projects we are taking advantage of. For example ROOT, Geant4, various MC generators, or non-HENP libraries like Boost.
</div>


## Consistency and Ease-of-Use

 To help users and developers the coding style, the development workflows and other technicalalities are chosen to be identical. This prevents duplication of efforts and confusion on user side. More details can be found in the technical documentation at [https://key4hep.github.io/key4hep-doc/](https://key4hep.github.io/key4hep-doc/)
