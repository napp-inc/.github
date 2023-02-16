name: New release version
description: Prepare la distribution d'une nouvelle version
title: '(release-version): '
labels: ['release']
body:
    - type: markdown
      attributes:
          value: |
              Ce issue t'aide à distribuer une nouvelle version!
    - type: dropdown
      id: release-type
      attributes:
          label: --Release--
          description: En se basant sur [semver](https://semver.org/lang/fr/) [MAJEUR.MINEUR.CORRECTIF]
          options:
              - Mineur
              - Majeur
      validations:
          required: true
    - type: textarea
      id: description
      attributes:
          label: --Description--
          description: Veuillez donné une briève description des changements apportés.
 

