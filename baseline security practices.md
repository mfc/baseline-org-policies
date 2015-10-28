# Baseline organizational policies and practices 
(that every group working in human rights should consider implementing)

## Table of Contents

0. Introduction

1. Access policies
  * Access to where you work
  * Access to devices
  * Access to accounts
  * Access to accounts
  * Removing access to organizational assets upon departure

2. Data management policies
  * Backing-up data (website, org data)
  * Travelling with data (data minimization, encryption)
  * Deleting data

3. Communications policies 
  * Define more and less sensitive communication methods
  * Email security

4. Creating and maintaining an engaged organizational culture
  * Update software on devices
  * Create spaces for learning, assessing, adopting, adapting policies and practices

5. Resources

## 0. Introduction

Organizations implement policies to help staff adopt practices to 
improve the effectiveness of the organization's work. This includes 
making staff feel safer in their work environment, and providing 
support and awareness for them to more safely work with their 
communities.

As individuals start to recognize the importance of some practices in 
the safety of their work, they understand that their own security and 
safety is based on the practices of their colleagues and their broader network. 

By providing baseline resources for the practices of organizations 
working in human rights, we hope to aid organizations in jumpstarting 
the continuous process of discussing, assessing, and implementating new 
organizational practices.

All individuals, groups, and organizations should assess their work, 
needs, and practices. Some resources for assessing these needs include:

* Security in a Box's resources for assessing risks: https://securityinabox.org/en/lgbti-africa/security-risk
* SAFETAG: https://github.com/OpenInternet/SAFETAG/blob/master/en/exercises/capacity_assessment_cheatsheet/instructions.md
* Integrated Security Manuael: http://www.integratedsecuritymanual.org/threats-exercises
* Surveillance Self-Defence: https://ssd.eff.org/en/module/introduction-threat-modeling

Through such an assessment, one can highlight gaps in need or practice, and 
prioritize topics for focus and improvement.

This resource seeks to inform the post-assessment stage for a human 
rights group group -- what are topics to consider for implementation 
and the baselines practices within those topics to aim for, at minimum.

Future plans for this resource include:

- [ ] adding more organizational policy templates
- [ ] getting it reviewed by the community, and feedback incorporated
- [ ] ramp-ups for topics about practices that further increase the 
security and safety of staff and communities
- [ ] stories and illustrations to better communicate the importance of 
these baseline practices and ways of implementing them

## 1. Access policies

### 1.1 Access to your place of work (such as at an office, at home)

* Set policies to manage entry and exit of visitors and staff
* Lock doors and windows when appropriate (such as when all 
staff leave)
* Report to other staff members anything strange in or around the place 
of work

### 1.2 Access to physical documents

* Staff should manage their workspace to ensure no sensitive physical 
documents are available to visitors
-- locked file cabinets
-- paper shredder

### 1.3 Access to devices

* wifi network

Organization's wifi should be dedicated to active staff of the 
organization. A guest network from the same router can be created to 
provide wifi access to visitors and other persons who are not staff
#link-to-SAFETAG

Wifi network password should be set up with WPA2 and the password 
should be a [strong passphrase](link). 
#link-to-SAFETAG

* computers, phones

All devices should have screenlocks to prevent casual access to 
information and accounts stored on the devices.
#link-to-how-to-enable-screenlock

All devices should have device encryption enabled to prevent more 
targeted access to information and accounts stored on the devices.
#link-to-how-to-enable-device-encryption

Organization-provisioned hardware (computers, routers, phones) should 
be recorded.

#### If a device is confiscated

{}

#### If a device is lost/stolen 

{}

### 1.4 Access to accounts

* organizational accounts (web presence [website, social media])
* password manager
* delegate control (tweetdeck, FB pages)
* two-factor authentication
* secret questions
* Personnel management onboarding/offboarding

### 1.5 Removing access to organizational assets upon departure
		
Departing staff must: 
* return any keys for physical building access
* return any devices provisioned to them by the organization
* Establish and inform point-of-contacts among other staff upon their departure
* Determine with supervisor what information can/cannot be discussed about their work for future job interviews, etc.

Appropriate org staff must:
* Disable departing staff access to email/social media accounts and any 
other digital infrastructure (chat server, file server, etc)
* Change passwords and/or access codes this individual may have access to
* Share or discuss interim plans with other staff until there is a new hire

## 2 Data management policies

### 2.1 Back-up data

* data the organization depends on should be backed-up in regular 
intervals.  
#link-to-how-to-backup

### 2.2 Travel 

General staff policies and emergency planning

#### travelling with data

Your devices and data are always at risk of being lost, stolen, 
confiscated. When you are travelling across borders, are in unfamiliar 
regions, etc. the risk of this happening will increase.

There are two strategies for protecting information, both in general 
and especially while travelling:

* data minimization
* encryption

Data minimization means you reduce the amount of sensitive information 
you are carrying with you, or your accounts have access to.

Encryption means protecting your device or data with an additional layer 
of access control.

### 2.3 Delete data securely

* have a document shredder at your place of work

* when to delete information
* how to delete data securely
-- Windows #link-to-SIAB-delete
-- Mac #link-to-Mac-Secure-Trash
-- wiping computers in general

## 3. Communications policies

### 3.1 Practices and policies

* Provide staff with work accounts (email, chat)
* Don't use your work account for personal communication or visa versa
-- this can be difficult if your work is in your community
-- at minimum make sure that you still have personal space online where 
you do not feel watched, judged, or "branded" by the org you work for
-- changing default FB sharing settings for posts and photos, creating 
groups, requiring consent to be tagged in a post or photo 
* Do not open unsolicited attachments or links
-- Clear hyperlink and attachment policies
* enable HTTPS for your organization's website
-- at minimum, ensure that the log-in page for administrating the 
website has HTTPS enabled.

### 3.2 Email

#### Organizational
* fight the email deluge by agreeing on informative subject lines

#### Technical
* Ensure that staff access email accounts through HTTPS

* Ensure that email provider uses STARTLS 

//------------- 
the following should be in SAFETAG / assessments:
(to test STARTLS:)

* test using https://checktls.com
* type in `test@<email-provider-URL>`

* look at column `TLS Neg`
  -- if `OK`, it uses STARTTLS
  -- if `FAIL`, then you will need to implement STARTLS on your mail 
server or move email providers

* look at column `Cert OK`
  -- if `OK`, it properly implements a TLS certificate
  -- if `FAIL`, you or your email provider needs to improve the TLS 
certificate used
-----------------//

## 4 Creating and Maintaining an Engaged Organizational Culture

### 4.1 Keep software up-to-date

* this includes your devices' operating systems and the software you and 
your website use
-- provide internet access to your staff to download software or 
operating system updates if necessary
-- provide licenses for proprietary software if that software is 
required and a staff member does not have a license

### 4.2 Create spaces for learning, assessing, adapting policies and practices


## 5. Resources

Some existing resources on risk assessment frameworks include:
-- the Responsible Data Forum's [Organizational Security Atomized Plan](https://github.com/mfc/responsible-data/tree/master/organizational-security-atomized-plan) 
-- Internews' [SAFETAG](https://github.com/OpenInternet/SAFETAG/)
-- EISF's [Risk Management Toolkit](https://www.eisf.eu/library/security-to-go-a-risk-management-toolkit-for-humanitarian-aid-agencies/)
-- the engine room's [self-assessment questionnaire](https://www.theengineroom.org/basic-organizational-security-survey/)
-- Security in a Box's [resources for assessing 
risks](https://securityinabox.org/en/lgbti-africa/security-risk)
* SAFETAG's [capacity assessment cheatsheet](https://github.com/OpenInternet/SAFETAG/blob/master/en/exercises/capacity_assessment_cheatsheet/instructions.md)
* [Integrated Security Manual](http://www.integratedsecuritymanual.org/threats-exercises)
* Surveillance Self-Defence's [intro to threat modeling](https://ssd.eff.org/en/module/introduction-threat-modeling)
* Security First's [Umbrella App](https://play.google.com/store/apps/details?id=org.secfirst.umbrella)

If you need assistance with assessing your groups needs and practices, 
feel free to contact:

* any organization listed in the [Digital First Aid Kit](https://github.com/RaReNet/DFAK/blob/master/SecureCommunication.md#seeking-and-providing-remote-help) 
* the engine room: post@theengineroom.org, [pgp key](https://pgp.mit.edu/pks/lookup?op=get&search=0xBA56E91DE8E8969F)
* Access Now's helpline staff: help@accessnow.org, [pgp key](https://pgp.mit.edu/pks/lookup?op=get&search=0xC46BED3332E8A2BC)
