# Chapter 2. Introduction to FOSS Licenses

## FOSS Licenses
- Free and Open Source Software (FOSS) licenses generally make source code available under terms that allow for modification and redistribution
- FOSS licenses may have conditions related to providing attributions, copyright statement preservation, or a written offer to make the source code available
- One popular set of FOSS licenses are those approved by the Open Source Initiative (OSI) based on their Open Source Definition (OSD). A complete list of OSI-approved FOSS licenses is available at http://www.opensource.org/licenses/

> FOSS License
- FOSS(Free and Open Source Software) License는 일반적으로 수정 및 재배포를 허용하는 조건하에 Source Code를 공개한다.  
- FOSS License는 고지 의무, Copyright 보존, Source Code 제공을 위한 약정서 제공과 같은 조건을 갖고 있기도 하다.  
- OSI (Open Source Initiative)는 OSD(Open Source Definition)를 정해놓고, 이에 부합하는 FOSS License를 승인해준다. OSI-approved FOSS License는 http://www.opensource.org/licenses/ 에서 확인할 수 있다. 


## Permissive FOSS Licenses
- Permissive FOSS license - a term used often to describe minimally restrictive FOSS licenses
- Example: BSD-3-Clause
  - The BSD license is an example of a permissive license that allows unlimited redistribution for any purpose as long as its copyright notices and the license's disclaimers of warranty are maintained 
  - The license contains a clause restricting use of the names of contributors for endorsement of a derived work without specific permission
- Other examples: MIT, Apache-2.0

> Permissive FOSS Licenses
- Permissive FOSS Licenses - 주로 제약이 아주 적은 FOSS License를 설명하기 위해 자주 사용되는 용어 
- 예: BSD-3-Clause
  - BSD License는 저작권 고지와 License의 보증부인을 유지하는 조건으로 제한 없는 재배포를 허락하는 Permissive License의 한 예이다. 
  - 이 License는 파생저작물의 홍보에 별도의 승낙 없이 기여자 이름의 사용하는 것을 제한하는 조항을 포함한다. 
- 다른 예: MIT, Apache-2.0


## License Reciprocity & Copyleft Licenses
- Some licenses require the distribution of derivative works (or software in the same file, same program or other boundary) under the same terms as the original work
  - This is referred to as a "copyleft", "reciprocal", or "hereditary" effect
- Example of license reciprocity from the GPL-2.0:

_"You must cause any work that you distribute or publish, that in whole or in part contains or is derived from the Program or any part thereof, to be licensed...under the terms of this License."_

- Examples: all versions of GPL, LGPL, AGPL, MPL, CDDL 

> License 상호주의 & Copyleft License
- 어떤 License는 파생저작물 (혹은 동일 File, 동일 Program이나 다른 Boundary 내 Software) 배포 시 원저작물과 같은 조항으로 배포할 것을 요구한다. 
  - 이러한 원리는 "Copyleft", "상호주의", "유전" 효과라고 불린다. 
- GPL-2.0 내 상호주의 조항 예: 

> _"You must cause any work that you distribute or publish, that in whole or in part contains or is derived from the Program or any part thereof, to be licensed...under the terms of this License."_

> 예: GPL, LGPL, AGPL, MPL, CDDL의 모든 version


## Proprietary License
- A proprietary software license (or commercial license or EULA) has restrictions on the usage, modification or distribution of the software
- Proprietary licenses often involve payment or a license fee 
- Proprietary licenses are unique to each vendor - there are as many variations of proprietary licenses as there are vendors and each must be evaluated individually
- FOSS developers often use the term "proprietary license" to describe a commercial non-FOSS license

> Proprietary License
- Proprietary Software License (or 상용 License or EULA)는 Software의 사용, 수정, 배포에 대한 제한을 갖고 있다. 
- Proprietary License에는 비용 지급, License 금액 등에 대한 내용이 포함되기도 한다. 
- Proprietary License는 Vendor 별로 고유하다.  Vendor의 수만큼 다른 Proprietary License가 있을 것이고, 이를 사용하기 위해서는 각각 개별 검토가 필요하다. 
- FOSS 개발자들은 상업적 non-FOSS License를 설명하기 위해 "Proprietary License"라는 용어를 사용하기도 한다. 


## Other Licensing Situations
- Freeware - software distributed under a proprietary license at no or very low cost
  - The source code may or may not be available, and creation of derivative works is usually restricted
  - Freeware software is usually fully functional (no locked features) and available for unlimited use (no locking on days of usage) 
  - Freeware software licenses usually impose restrictions in relation to copying, distributing, and making derivative works of the software, as well as restrictions on the type of usage (personal, commercial, academic, etc.)
- Shareware - proprietary software provided to users on a trial basis, for a limited time, free of charge and with limited functionalities or features
  - The goal of shareware is to give potential buyers the opportunity to use the program and judge its usefulness before purchasing a license for the full version of the software 
  - Most companies are very leery of Shareware, because Shareware vendors often approach companies for large license payments after the software has freely propagated within their organizations.
- Freeware and Shareware are not FOSS

> 다른 형태의 License
- Freeware - Proprietary License이지만, 무료 혹은 아주 저렴하게 배포된 Software
  - 일반적으로 소스 코드는 공개되지 않고, 파생저작물의 생성을 금지한다. 
  - Freeware Software는 대개 모든 기능이 동작하고 (사용 불가 기능 없음), 기한 제한 없이 사용할 수 있다.
  - Freeware Software는 복사, 배포, 파생저작물 생성에 대해서 뿐만 아니라 사용 형태 (개인, 상용, 학업 등)에 대해서도 제한을 부과한다. 
- Shareware - 시험판으로 사용자에게 제공되는 Proprietary Software로써, 사용 기간에 제한이 있고, 제한된 기능을 무료로 사용할 수 있게 한다. 
  - Shareware의 목적은 잠재적인 고객에게 Program 사용 기회를 제공하여 full version software의 구매를 결정할 수 있게 하는 것이다. 
  - 일부 Shareware vendor들은 일단 무료로 사용하게 하여 확산을 시킨 후 고비용의 License 금액을 청구하는 경우가 있으므로 대부분 기업은 Shareware를 상당히 경계한다. 
- Freewware와 Shareware는 FOSS가 아니다. 


## Public Domain
- The term public domain refers to intellectual property not protected by law and therefore usable by the public without requiring a license 
- Developers may include a public domain declaration with their software 
  - E. g., "All of the code and documentation in this software has been dedicated to the public domain by the authors."
  - The public domain declaration is not the same as a FOSS license
- The enforceability of these public domain declarations is subject to dispute within the FOSS community
- Often the public domain declaration is accompanied by other terms, such as warranty disclaimers. In such cases, the software may be viewed as being under a license rather than being in the public domain

> Public Domain
- Public Domain은 법에 따라 보호받지 않는 지적 재산을 가리키며 누구든지 License 없이 사용할 수 있다.
- 개발자들은 자신의 Software에 대해 Public Domain에 해당한다는 선언을 포함할 수 있다. 
  - 예 : "All of the code and documentation in this software has been dedicated to the public domain by the authors."
  - Public Domain 선언이 FOSS License와 같은 것은 아니다. 
- 이러한 Public Domain 선언의 법적 집행 가능성은 FOSS Community 내에서 논쟁이 있는 부분이기도 하다. 
- 종종 Public Domain 선언이 보증 부인 등 다른 조항과 함께 사용될 수 있는데, 이 경우는 Software가 Public Domain 상태라기보다는 하나의 License 하에 있다고 볼 수 있다. 


# License Compatibility
- License compatibility is the process of ensuring that license terms do not conflict. If one license requires you to do something and another prohibits doing that, the licenses conflict and are not compatible, if the combination of the two software modules trigger the obligations under a license; for example,GPLv2 extends its obligations to "derivative works" and if a second software module is combined with a GPLv2 licensed module that is not a derivative work of the GPLv2 licensed module, the second software module is not subject to GPLv2.  The definition of "derivative work" is subject to different views in the FOSS community} 
- The Free Software Foundation provides the following example to illustrate a case of license compatibility:

*A license p is compatible with a license q (or is q-compatible) if*
*A work licensed under p can be distributed under the terms of q.*

- Example: GPL compatibility
  - Many of the FOSS licenses, such as the MIT license and the LGPL, are GPL-compatible, meaning that their source code can be combined with source code that is licensed under the GPL without conflict; the new program resulting from the combination would have to be licensed under the GPL.
  - Other FOSS and proprietary software licenses are not GPL-compatible since they have conflicting terms and conditions, but  such inconsistency is only important if these programs are combined in a way which creates a derivative work with the GPLv2 software.
  - Reference: http://www.fsf.org/licensing/licenses/

> License Compatibility
- License Compatibility는 License 조항들이 충돌하지 않음을 보장하는 Process이다. 
  - 만약 한 License가 요구하는 내용을 다른 License가 금지한다면, 두 개의 Software 모듈의 결합이 License 의무 사항을 유발할 경우, 이 License들은 충돌하는 것이고 호환되지 않는다.
- 한 예로 GPLv2는 “파생저작물”에도 의무 사항을 부여한다. 
  - 만약, GPLv2 Licensed 모듈과 결합한 두번째 Software 모듈이 GPLv2 Licensed 모듈의 파생저작물이 아니라면, 이 두번째 Software 모듈은 GPLv2의 대상이 아니다. “파생저작물”의 정의는 FOSS Community의 관점에 따라 다르다.
- Free Software Foundation은 License Compatibility를 설명하기 위해 다음 사례를 제공한다. 

>   *License p로 배포된 저작물은 q의 조항으로도 배포할 수 있다면, License p는 License q와 호환 (혹은 q-compatible)된다.*

>- 예: GPL compatibility
  - MIT와 같은 많은 FOSS License들 그리고 LGPL은 GPL-compatible하다. 즉, 이런 FOSS License 하의 소스 코드는 GPL하의 소스 코드와 충돌 없이 결합할 수 있다; 이러한 결합으로 생성된 새로운 Program은 GPL이 적용되어야 할 것이다. 
  - 다른 FOSS License와 Proprietary Software License는 GPL의 조항과 조건이 충돌하기 때문에 GPL-compatible 하지 않다. 단, 이러한 충돌은 GPL-2.0 Software의 파생저작물을 생성하는 결합하는 경우에 한해서만 고려될 필요가 있다. 
  - 참고 : http://www.fsf.org/licensing/licenses/

## Notices
Notices, such as text in comments in file headers, often provide authorship and licensing information. FOSS licenses may also require the placement of notices in source code or documentation to give credit to the author (an attribution) or to make it clear the software includes modifications. 
- Copyright notice - an identifier placed on copies of the work to inform the world of copyright ownership. Example: Copyright © A. Person (2016). 
- License notice - a notice that acknowledges the license terms and conditions of the FOSS included in the product.
- Attribution notice - a notice included in the product release that the identity of the original authors of the FOSS included in the product.
- Modification notice – a notice that you have made modifications to the source code of a file, such as adding your copyright notice to the top of the file. 

> 고지 (Notice)
파일 상단의 Text 주석과 같은 고지는 주로 작성자 및 License 정보를 제공한다. FOSS License는 또한 저작자 정보의 제공이나 수정 내용을 포함시키기 위해 소스 코드 혹은 문서 내에 고지를 포함할 것을 요구하기도 한다. 
- 저작권 고지 - 저작권자가 누구인지를 알리기 위해 저작물의 사본에 붙이는 식별자. 예: Copyright © A. Person (2016).
- License 고지 - 제품에 포함된 FOSS의 License 조항과 조건을 알리기 위한 고지
- 귀속정보 (Attribution) 고지 - 제품에 포함된 FOSS 원저작자의 신원을 나타내기 위해 제품 배포 시 포함하는 고지
- 수정 내용 고지 - 파일 상단에 새로운 저작권 표시를 추가하는 등, 파일의 소스 코드를 수정하였음을 알리는 고지


## Multi-Licensing
- Multi-licensing refers to the practice of distributing software under two or more different sets of terms and conditions
  - E.g., when software is “dual licensed,” recipients can choose to use or distribute the software under a choice of two licenses
- Note: This should not be confused for situations in which a licensor imposes more than one license, and you must comply with all of them

> Multi License
- Multi License란 둘 이상의 다른 조항과 조건으로 Software를 배포하는 경우를 말한다.
  - 예를 들어, Software가 "Dual License"인 경우, 수신자는 두 License 중 하나를 선택하여 Software를 사용하거나 배포할 수 있다. 
- 참고 : Licensor가 두 개 이상의 License를 부과하는 상황과 혼동해서는 안된다. 이런 경우는 모든 License를 준수해야 한다. 

## Check Your Understanding
- What is a FOSS license?
- What are typical obligations of a permissive FOSS license?
- Name some permissive FOSS licenses.
- What does license reciprocity mean?
- Name some copyleft-style licenses.
- Are Freeware and Shareware software considered FOSS?
- What is a multi-license?

> Check Your Understanding
- FOSS License란 무엇인가?
- Permissive FOSS License의 주요 의무 사항은 무엇인가?
- Permissive FOSS License에는 무엇이 있는가?
- License 상호주의는 무엇을 의미하는가?
- Copyleft-style License에는 무엇이 있는가?
- Freeware와 Shareware를 FOSS로 간주되는가?
- Multi-License란 무엇인가?
