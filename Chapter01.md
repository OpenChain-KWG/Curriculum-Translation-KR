p.4

# Chapter 1. What is Intellectual Property?

###### Notes : This chapter is focused on the “big picture” of Intellectual Property. This chapter is probably most useful for managers or developers who might not understand clearly the fundamentals of copyright, patent and trademark law.
###### > 이 Chapter는 지적 재산권의 "큰 그림"에 초점을 맞추고 있다. 이 Chapter는 저작권, 특허 및 상표법의 기본에 대해 명확하게 이해하지 못하는 관리자 또는 개발자에게 유용 할 것이다.


p.5
## What is “Intellectual Property”?

- Copyright: protects original works of authorship
  - Protects expression (not the underlying idea)
  - Software, books, audiovisual materials, semiconductor masks
- Patents: useful inventions that are novel, useful, non-obvious 
  - Limited monopoly to incentivize innovation
- Trade secrets: protects confidential and valuable information
- Trademarks: protects marks (word, logos, slogans, color, etc.) that identify the source of the product	
  - Consumer and brand protection; avoid consumer confusion and brand dilution

**This chapter will focus on copyright and patents, the areas most relevant to FOSS compliance**


> “Intellectual Property”란?
-  저작권: 저자의 원저작물을 보호
  - (근본적인 아이디어가 아닌) 표현을 보호
  - Software, 책, 시청각 자료, 반도체 마스크
- Patents : 새롭고, 유용하며, 너무 뻔하지 않은 (non-obvious) 발명 
  - 혁신을 장려하기 위한 제한 독점
- 영업 비밀 : 기밀의 가치 있는 정보를 보호
- 상표 : 품의 출처를 나타내는 상표(단어, 로고, 슬로건, 색상 등)를 보호
  - 소비자와 브랜드 보호; 소비자를 혼란스럽게 하거나 상표 가치 하락하는 것을 방지하기 위함

> **이 장에서는 FOSS Compliance와 주로 관련이 있는 저작권과 특허를 중점으로 설명한다.**

## Copyright concepts in software

- Basic rule = copyright protects creative works
- Copyright generally applies to literary works, such as books, movies, pictures, music, maps
- Software is protected by copyright, not the functionality (that’s protected by patents) but the expression (creativity in implementation details)
- The copyright owner only has control over the work that he or she created, not someone else’s independent creation


> Software에서의 저작권 개념
- 기본 규칙: 저작권으로 창작 저작물을 보호한다 
- 저작권은 일반적으로 도서, 영화, 그림, 음악, 지도와 같은 문학 작품에 용된다. 
- Software는 저작권에 의해 보호되며 기능(기능은 특허에 의해 보호)이 아닌 표현 (세부 구현 내용의 창의성) 이 보호된다. 
- 저작권 소유자는 자신이 만든 저작물에 대해서만 통제권을 갖는다. (타인의 독립적인 저작물에 대해서는 통제권이 없음) 

## Copyright rights most relevant to software

- The right to reproduce the software – making copies
- The right to create "derivative works" – making modifications
  - The term derivative work refers to a new work based upon an original work to which enough original creative work has been added so that the new work represents an original work of authorship rather than a copy (note that this is a term of art under US law)
- The right to distribute
  - Distribution is generally viewed as the provision of a copy of a piece of software in binary or source code form to another entity (an individual or organization outside your company or organization)  

**Note: The interpretation of what constitutes a “derivative work” or a “distribution” is subject to debate in the FOSS community and within FOSS legal circles**

> Software와 가장 관련 있는 저작권 권리
- Software를 복제할 수 있는 권리 - 복제
- 파생저작물을 만들 수 있는 권리 - 수정
  - '파생저작물'이란 어떠한 한 저작물을 기반으로 만들었지만, 충분히 독창적인 부분이 추가되어서, 단지 복사가 아닌 저자의 새로운 저작물로 간주할 수 있는 것을 의미한다. (US law에서 사용하는 용어임에 유의)
- 배포할 수 있는 권리
  - 일반적으로 Software 일부를 복사하여 Source Code 혹은 Binary Form으로 다른 주체(개인 혹은 회사/기관 밖의 기관)에 제공하는 것을 배포라고 본다. 

>**참고: "파생저작물"이나 "배포"가 무엇인지에 대한 해석은 FOSS community나 FOSS 법률가들 사이에서 논의의 대상이다**

## Patent concepts in software
- Patents protect functionality - this can include a method of operation, such as a computer program
  - Does not protect abstract ideas, laws of nature
- The patent owner has the right to stop anybody from exercising that functionality, regardless of independent creation 
- Other parties who want to use the technology may seek a patent license (which may grant rights to use, make, have made, sell, offer for sale, and import the technology)

> Software에서의 특허 개념
- 특허는 기능을 보호함 - Computer Program과 같은 동작 방법 등
  - 추상적인 아이디어나 자연법칙을 보호하지는 않는다. 
- 특허 소유권자는 누군가 독창적으로 만든 것과 상관없이 해당 기능의 수행을 금지할 권리가 있다. 
- 해당 기술을 사용하고자 한다면 특허 License (해당 기술을 사용, 제작, 판매, 수입할 수 있는 권리)를 취득해야 한다. 

## Licenses
- A "license" is the way a copyright or patent holder gives permission or rights to someone else
- The license can be limited to:
  - Types of use allowed (distribution, derivative works / to make, have made, manufacture)
  - Exclusive or non-exclusive terms
  - Geographical scope
  - Perpetual or time limited duration
- The license can have conditions on the grants, meaning you only get the license if you comply with certain obligations
  - E.g, provide attribution, give a reciprocal license
- May also include contractual terms regarding warranties, indemnification, support, upgrade, maintenance

> License
- "License"는 저작권자, 특허권자가 사용허가 혹은 권리를 부여하는 것을 말한다. 
- License는 다음 사항들에 따라 제한 될 수 있다. 
  - 허용되는 사용 형태 (배포, 파생저작물 제작)
  - 독점 혹은 비독점 조항
  - 관할 지역
  - 영구적 혹은 시간제한
- License는 권한을 부여하기 위한 조건을 갖고 있다. 즉, 해당 조건을 준수하는 경우에만 License를 가질 수 있다. 
  - 예, 저작자 표시 제공, 동일 License 적용
- 보증, 면책, 지원, 유지 보수 등과 관련하여 계약상의 조항이 포함되는 경우도 있다.

## Check Your Understanding
- What type of material does copyright law protect?
- What copyright rights are most important for software?
- Can software be subject to a patent? 
- Does a patent give rights to the patent owner?
- If you independently develop your own software, is it possible that you might need a copyright license from a third party for that software? A patent license?

> Check Your Understanding
- 저작권법은 어떤 유형의 자료를 보호하는가?
- Software에서 가장 중요한 저작권 권리는 무엇인가?
- Software가 특허의 대상이 될 수 있는가?
- 특허는 특허 소유자에게 권리를 부여하는가?
- 독자적으로 개발한 Software에 대해 제3자로부터 저작권 License 취득이 필요할 수도 있는가? Patent License는?

