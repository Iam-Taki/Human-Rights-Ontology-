# Human Rights Ontology 2.0 (HRO 2.0)

## Overview
The Human Rights Ontology 2.0 (HRO 2.0) is a structured, machine-readable knowledge base that organizes human rights concepts, their legal foundations, and interrelationships. Built in OWL (Web Ontology Language), it enables semantic reasoning, legal analysis, and integration with human rights monitoring systems.

## Key Features
- Comprehensive Rights Coverage - Civil, political, economic, social, cultural, and environmental rights
- Hierarchical Structure - Logical classification with parent-child relationships
- Legal References - Links to treaties, conventions, and article numbers
- Real-World Examples - Instances with descriptions, legal sources, and historical context
- Semantic Web Ready - Compatible with SPARQL, Protégé, and reasoning engines

## Ontology Structure

### Core Classes & Subclasses

1. HumanRights (Root Class)
   - The overarching class for all human rights concepts.

2. ConstitutionalRights
   - Fundamental rights recognized in constitutions.
   - HumanDignity
     - ProtectionFromUnlawfulKilling
     - RightToPersonalSafety
   - ImpartialJustice
     - InnocentUntilProvenGuilty
     - RightToLegalAssistance
   - InviolabilityOfPrivateLife
     - PersonalDataProtectionRights
     - RightToPrivacy
   - LibertyOfExpression
     - FreedomOfExpression
     - FreedomOfPress

3. EconomicalRights
   - Rights related to work, property, and economic security.
   - RightToEmployment
     - RightToAHealthyAndSafeWorkplace
     - RightToDecentPay
   - RightToFairAndSafeWorkingConditions
     - RightToNonDiscriminatoryPay
     - RightToWorkLifeBalance
   - RightToOwnProperty
     - ExclusiveRightsOverIndustrialCreations
       - ExclusiveRightsOfPatent
       - RightToExclusiveUseOfCopyright
     - RightToPrivateProperty
   - RightToSocialSecurity
     - RightToRetirementBenefits
     - RightToSocialAssistanceForDisability

4. RightsOfPoliticalParticipation
   - Rights related to governance and civic engagement.
   - ActiveSuffrage
     - DemocraticElections
     - InclusiveSuffrage
   - CivicEngagementRights
     - RightToCivicEngagement
     - RightToContestElections
   - RightToOrganize
     - RightToJoinUnions
     - RightToPoliticalAssociation
   - RightToPublicDemonstration
     - FreedomOfProtest
     - FreedomOfPublicGatherings

5. RightsToCulturalHeritage
   - Rights related to culture, science, and intellectual property.
   - RightToAccessScientificKnowledgeAndAdvances
     - RightToScientificInformation
     - RightToShareInScientificProgress
   - RightToCulturalParticipationAndExpression
     - RightToBenefitFromCulturalHeritage
     - RightToMaintainCulturalDistinctiveness
   - RightToCulturalRecognition
     - RightToLinguisticIdentity
     - RightToPracticeCulture

6. RightsToSocialProvisions
   - Rights ensuring social welfare and public services.
   - AccessToEducation
     - RightToElementaryEducation
     - RightToIntermediateEducation
   - AccessToHealthcare
     - RightToHealthPromotionAndPrevention
     - RightToHealthProtection
   - ProtectionOfFamilyUnity
     - FreedomToMarry
     - RightToMaternityAndPaternityLeave
   - RightToSocialAndHousingAssistance
     - ProhibitionOfUnlawfulEviction
     - RightToAppropriateHousing

7. RightToAHealthyEnvironment
   - Rights related to environmental protection.
   - RightToAHazardFreeEnvironment
     - RightToAToxicFreeEnvironment
     - RightToEnvironmentalLiabilityEnforcement
   - RightToCleanEnvironment
     - RightToHealthyAir
     - RightToSafeWater
   - RightToSustainableDevelopment
     - EnvironmentalInformationTransparency
     - RightToEnvironmentalConsultation


