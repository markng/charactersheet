# As an administrator, I can create a character sheet, so that I can track a players character details.

## AC
* It is in the admin interface
* It requires an admin login to create
* It has the following text fields, all of which can be null
  * Character Name
  * Trope
  * Pronouns
  * Fear
  * Motivation
  * Description
  * Grade
  * Animal Familiar
  * Strengths
* It has the following integer fields
  * Age
  * Fight
  * Flight
  * Brains
  * Brawn
  * Charm
  * Grit

## Tasks
* Set up pytest-describe testing framework.
* Set up admin interface using standard django admin
* Create CharacterSheet model
  * add fields
* Create migration for CharacterSheet model
* Add CharacterSheet model to Django Admin