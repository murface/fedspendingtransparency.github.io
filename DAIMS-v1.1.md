---
published: true
permalink: /DAIMS-v1.1/
layout: article
filename: DAIMS-v1.1.md
title: DATA Act Information Model Schema v1.1
page: DAIMS-v1.1
---

# DATA Act Information Model Schema v1.1

_Updated June 30, 2017_ – A core requirement of the DATA Act is the development of government-wide data standards to ensure the reporting of reliable, consistent federal spending data for public use. Office of Management and Budget (OMB) and Treasury finalized the 57 data definition standards and Treasury used the data definition standards to develop the initial draft of the DATA Act data exchange standard, or Schema, in May 2015. Treasury collected public input and feedback from federal agencies and implemented an agile development methodology to create the DATA Act Information Model Schema (DAIMS) v1.0. DAIMS v1.1 is a minor update to transition financial assistance reporting to the DATA Act Broker, to better align with another federal government source system, and to provide clarifications for improved usability. DAIMS v1.1 will be implemented in production in September 2017.

DAIMS gives an overall view of the hundreds of distinct data elements used to tell the story of how federal dollars are spent. It includes artifacts that provide technical guidance for federal agencies about what data to report to Treasury including the authoritative sources of the data elements and the submission format. The DAIMS also provides clarity on how the public can better understand the inherent complexity of the data.

##### DAIMS includes:
 - **Information Flow** – provides an overview of the reporting timeframes and sources of the data included in the DAIMS across the federal enterprise.
 - **Reporting Submission Specification (RSS)** – includes a listing of the data elements with specific instructions for federal agencies to submit content in the appropriate format. The RSS is a human-readable version of the data standard.
 - **Interface Definition Document (IDD)** – contains a listing of the elements, with supporting metadata to understand what data will be pulled from government-wide systems for procurement and from agency financial assistance systems. The IDD is a human-readable version of the data standard for the award related content.
 - **Domain Values** - include permissible values for a sub-set of the DAIMS data elements.
 - **Terse Labels** - provide shortened versions of data element names.
 - **DAIMS Diagrams** – display visual representations of how the data elements from the RSS and IDD fit together in context.
 - **Online Data Dictionary** – contains a comprehensive list of data elements with definitions and some associated metadata.
 - **XBRL Schema Files** – provide a machine-readable version of the data standard that includes accounting-related and award-related content.

## Information Flow

The Information Flow provides an overview of the sources of the data included in the DAIMS and how the data will be submitted to the DATA Act Broker. Treasury will maintain the current cadence for reporting federal awards on a daily and twice-monthly basis and added the quarterly reporting of financial data in May 2017. This updated model shows how the data flows from the agency financial and awards systems to the public website and will be implemented in September 2017.  

<img width="800" src="{{ site.baseurl }}/assets/img/informationflow.png" title="information flow diagram" />

## Reporting Submission Specification (RSS)

The RSS provides details on what data needs to be submitted from an agency’s financial system.  The RSS contains prescriptive guidance to report appropriations account, object class, program activity, and award financial data.  The award financial data contains instructions to link the data between the financial systems and the award systems using the award identification number.  The RSS  includes information about optional/required data, field length,  and other metadata to ensure data quality.  The RSS documents contain the specific instructions a federal agency will need to submit data.

The RSS includes three files that the agencies will submit to Treasury’s Broker:

- File A – Appropriations Account Detail
- File B – Object Class and Program Activity Detail
- File C – Award Financial Detail

Download the RSS v1.1

Federal agencies can view [more information about the RSS on MAX](https://community.max.gov/x/CIbyL){:target="_blank"}.

## Interface Definition Document (IDD)

The Interface Definition Document (IDD) provides an overview of the award specific data elements and explains how the data will be reported or collected. Some data elements will be pulled from government-wide intermediary systems for procurement data, recipient attributes and sub award information.  The IDD also includes data elements submitted by agency systems for financial assistance awards.

The IDD is based on the Data Model (DAIMS) v1.01 and features the elements related to:

- File D1 – Award and Awardee Attributes (Procurement)
- File D2 – Award and Awardee Attributes (Financial Assistance)
- File E – Additional Awardee Attributes
- File F – Sub-award Attributes

Federal agencies can view more information about [the IDD on MAX](https://community.max.gov/x/CIbyL){:target="_blank"}.

Download the IDD v1.1

## Domain Values

The domain values include permissible values for a sub-set of the DAIMS data elements.

## Terse Label

The terse labels provide shortened versions of data element names. 

## DAIMS Diagrams

The diagrams are visual representations of how the different data elements are related. They show the groupings of elements and attributes.

<div class="list-group" style="width:50%;">
  <a href="{{site.baseurl}}/assets/docs/DAIMS_RSS_Diagram_File_A_v1.0_04292016.pdf" target="_blank" class="list-group-item">File A – Appropriations Account Detail</a>
  <a href="{{site.baseurl}}/assets/docs/DAIMS_RSS_Diagram_File_B_v1.0_04292016.pdf" target="_blank" class="list-group-item">File B – Object Class and Program Activity Detail</a>
  <a href="{{site.baseurl}}/assets/docs/DAIMS_RSS_Diagram_File_C_v1.0_04292016.pdf" target="_blank" class="list-group-item">File C – Award and Financial Detail</a>
  <a href="{{site.baseurl}}/assets/docs/DAIMS_IDD_Diagram_File_D1_v1.01.pdf" target="_blank" class="list-group-item">File D1 – Award and Awardee Attributes (Procurement)</a>
  <a href="{{site.baseurl}}/assets/docs/DAIMS_IDD_Diagram_File_D2_v1.01.pdf" target="_blank" class="list-group-item">File D2 – Award and Awardee Attributes (Financial Assistance)</a>
  <a href="{{site.baseurl}}/assets/docs/DAIMS_IDD_Diagram_File_E_v1.01.pdf" target="_blank" class="list-group-item">File E – Additional Awardee Attributes</a>
  <a href="{{site.baseurl}}/assets/docs/DAIMS_IDD_Diagram_File_F_v1.01.pdf" target="_blank" class="list-group-item">File F – Sub-award Attributes</a>
</div>

## Online Data Dictionary
The [Data Dictionary v1.1]({{ site.baseurl }}/dictionary/){:target="_blank"} is a comprehensive list of data elements with definitions and some associated metadata.

## XBRL Schema and Data Files

A data standard contains both a human-readable version of the standard and a machine-readable version of the standard. The XBRL Schema files are the machine-readable version of the DATA Act standard.

[Zipped Schema Files with Release Notes (Updated on June 30, 2017)]({{site.baseurl}}/assets/docs/daims_v1.01.06_2017-05-31.zip)

[Zipped Instance Documents with Data for Fiscal Year 2017 Quarter 2 (January to March 2017, Updated on June 30, 2017)](http://da-public-files.s3-website-us-gov-west-1.amazonaws.com/xbrl_files/data-act-xbrl-instance-Q2-2017-05-18.zip)

## Data Definition Standards

The Federal Funding Accountability and Transparency Act (FFATA) and DATA Act outline the required information for federal spending transparency reporting. These requirements were translated into core data definition standards that were standardized with feedback from the federal community and external stakeholders. The finalized definitions and background information for these elements are available on the [Data Elements Page]({{ site.baseurl }}/data-elements/){:target="_blank"}.