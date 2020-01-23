---
layout: single
#title: Welcome to ResearchPackage
---

# Welcome to ResearchPackage

ResearchPackage is a Flutter [package](https://pub.dartlang.org/packages/research_package) for building research study apps on Android and iOS using [Flutter](https://flutter.dev).

ResearchPackage is a Flutter implementation of the [Apple ResearchKit](https://www.researchandcare.org/researchkit/) available for iOS (just like  [ResearchStack](http://researchstack.org/)). The overarching goal of ResearchPackage is to enable developers and researchers to design and build cross-platform (iOS and Android) research applications using the same codebase. The API and UX design of ResearchPackage follows the API and UX of ResearchKit almost 1:1 (with a few adaptations to Flutter, including applying more to a reactive programming model).

ResearchPackage is designed from the ground up to meet the requirements of most scientific research, including capturing participant consent, extensible input tasks, and the security and privacy needs necessary for IRB approval. 
The main features of ResearchPackage are:

- [Obtaining informed consent](consent) from participants, including support for a signature.
- [Creating surveys](survey) and questionnaires with a wide range of answer formats (e.g., likert scale, date pickers, image pickers, etc.)

ResearchPackage is part of the overall CACHET Research Platform (CARP) with also provides a Flutter package for mobile and wearable sensing -- called [CARP Mobile Sensing](https://pub.dev/packages/carp_mobile_sensing). By combining ResearchPackage with CARP Mobile Sensing, support for what is called ["Active Tasks"](https://www.researchandcare.org/researchkit/) in ResearchKit can be implemented.




