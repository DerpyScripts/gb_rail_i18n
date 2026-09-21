# GB Rail Internationalisation (i18n)
Translations, both fun and serious, for various aspects of railway information in Great Britain

## darwin_reasons.json
This file contains a list of all delay/cancellation reasons used by the 'Darwin' real-time information system for the railway in Great Britain. These can be used together with the arrival/departure board APIs and "PushPort" data stream available on the [Rail Data Marketplace](https://raildata.org.uk).

The current target languages are:
- [cy] Welsh (available for reason codes 100 to 801, as used by TfW Rail. Remaining reasons will be added soon)
- [en] English
- [nl] Dutch

Feel free to add more languages, using their 2-letter ISO 639 code in lowercase. Please keep the strings ordered alphabetically by language code when adding new languages.

## cis_pis_simulator.json
This file will be used by [cis.arturs.co.uk](https://cis.arturs.co.uk), which is a website that allows you to simulate various European departure/arrival/onboard screens using open data from other European railway operators. E.g. Finnish trains on a Dutch departure board, or British trains on a Swiss arrivals board.

> Please note that the above site is currently being re-built to support data from railways outside Great Britain, and the work-in-progress version that supports other sources is available at [evo--cis-pis-simulator.netlify.app](https://evo--cis-pis-simulator.netlify.app). This is a staging environment so do expect bugs.

The current target languages are:
- [cy] Welsh
- [de] German
- [en] English
- [fi] Finnish
- [fr] French
- [it] Italian
- [nl] Dutch
- [sv] Swedish

The above list encompasses the official languages used by the countries whose departure boards are available in this project. Any strings that are missing a translation in any of the target values have a `false` value to make them more easily noticeable.

Feel free to add more languages, using their 2-letter ISO 639 code in lowercase. Please keep the strings ordered alphabetically by language code when adding new languages. Some strings have a `_translationNotes` field, which provides additional context for how to translate the text into new languages.
