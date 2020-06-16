# DJStreamr Legal Issues Report

## Third Party Resources

DJStreamr uses the following open-source software and libraries:

- [AWS Java SDK v2](https://github.com/aws/aws-sdk-java-v2) - Subject to an
Apache 2.0 License
- [AWS Java Lambda Libs](https://github.com/aws/aws-lambda-java-libs) -
Subject to an Apache 2.0 License
- [Beads](https://github.com/orsjb/beads), a Java sound processing library -
Subject to a GNU Public License (GPL v3)
- [Auth0 `java-jwt`](https://github.com/auth0/java-jwt), a Json Web Token
processing library - Subject to a MIT License
- [The Kotlin language](https://github.com/JetBrains/kotlin) - Subject to an
Apache 2.0 License. We use the following language extension libraries,
subject to the same license:
  - [`kotlinx.serialisation`](https://github.com/Kotlin/kotlinx.serialization),
    for JSON serialisation
  - [`kotlinx.coroutines`](https://github.com/Kotlin/kotlinx.coroutines),
    for concurrency
- [MockK](https://github.com/mockk/mockk), a mocking library - Subject to an Apache 2.0 License
- [Gradle](https://github.com/gradle/gradle), the build tool - Subject to an
Apache 2.0 License
- [AWS Amplify](https://www.npmjs.com/package/aws-amplify), aws interface for
the frontend - Subject to the Apache 2.0 License
- [Fontawesome](https://www.npmjs.com/package/@fortawesome/fontawesome-free),
font awesome pack for icons. Icons are subject to the CC BY 4.0 license,
Fonts are subject to the SIL OFL 1.1 license and the code is subject to the
MIT license.
- [Axios](https://www.npmjs.com/package/axios), for maxing async http
requests. Subject to the MIT license.
- [Bootstrap](https://www.npmjs.com/package/bootstrap), a css framework.
Subject the to the MIT license.
- [Bootstrap-vue](https://www.npmjs.com/package/bootstrap-vue), for better
integration between Bootstrap and Vue. Subject to the MIT license.
- [core-js](https://www.npmjs.com/package/core-js), for JavaScript standard
library features. Subject to the MIT license.
- [range-slider-vue](https://www.npmjs.com/package/range-slider-vue), for
sliders in Vue. Subject to the MIT license.
- [Roboto font](https://www.npmjs.com/package/typeface-roboto), for the
Google Roboto font. Subject to the MIT license.
- [Vue](https://www.npmjs.com/package/vue), a JavaScript framework to make
UIs and Single Page Applications. Subject to the MIT license.
- [vue-clickaway](https://www.npmjs.com/package/vue-clickaway), for detecting
click outside of Vue components. Subject to the MIT license.
- [vue-clipboard2](https://www.npmjs.com/package/vue-clipboard2), for
interacting with the clipboard from Vue. Subject to the MIT license.
- [vue-router](https://www.npmjs.com/package/vue-router), for Vue SPA
routing. Subject to the MIT license.
- [vue-toasted](https://www.npmjs.com/package/vue-toasted), for Vue
notification. Subject to the MIT license.
- [Vuelidate](https://www.npmjs.com/package/vuelidate), for Vue form
validation. Subject to the MIT license.
- [Wavesurfer.js](https://www.npmjs.com/package/wavesurfer.js), for working
with sound in JavaScript. Subject to the BSD-3-Clause license.

## License Implications and Legal Concerns

As the Licensees, we are distributing these libraries (without modifications)
to Amazon, by using their web services. Our work is also a Derivative of the
works, and we are also distributing it to Amazon. Additionally, subset of our
work (the fornt-end code) is also distributed in source form to our users.

### Apache 2.0

Under the terms of this Apache License, we are allowed this distribution as
long as we include a notice along with our work. This notice must include a
copy of the License as well as copyright notices of the authors of the Works
we use.

We may also use our derived work for commerical purposes.

On the other hand, we are not allowed to use the names (or logos) of the
authors of the Works (but we may use them to make the notice).

Finally, we may not hold liable the authors of the Works we use for any
problem we might encounter.

Overall, aside from the obligations we must fulfill in producing the notice,
being subject to this License should not pose any legal risks with regard to
our work.

### MIT

Similarly to being subject to the Apache v2 License, we may distribute our
derived work (and copies of `java-jwk`, the work we use that has this
license) as long as we include Auth0's copyright notice as well as a copy of
the license.

We may also use our derived work for commerical purposes.

We may use Auth0's trademarks or logos too, but we may not hold them liable
for any issues we might encounter.

Aside from the obligation of including the copyright and the License, being
subject to this License should not pose any legar risks with regard to our
work.

### GNU Public License v3

Of the three licenses we are subject to, GPL v3 is the most restrictive.

We may distribute the Work we use (the **Beads** library) and our derived work,
as long as we include a notice that:

   - points to the original work
   - states the changes made to the original work (we did not make any)
   - includes a copy of the GPL v3 License
   - includes [Ollie Brown](https://github.com/orsjb)'s original copyright 
  
We are not obligated to include install instructions, as our software is
not part of a consumer device.

We may not distribute a copy of Beads under a different License (something we
do not intend to do), or hold Ollie Brown liable for any problems we might
encounter.

Additionally, a small part of our work (the syncing service) performs dynamic
linking with the Beads library. Therefore, there is a legal risk in using
this library if we do not intend to make our syncing service open-source and
license it under GPL v3.

Note that the syncing serice is not linked against any other parts of our
source code, and thus the rest of our code should not constitute work _derived
from_ Beads.

Thus, should we wish to realease our work, it is recommended the syncing
service be rewritten without using Beads.

It is worth noting that the Free Software Foundation considers that _dynamic_
linking (which is our case) violates GPL. But
[other points of view 
that argue otherwise do exist](https://en.wikipedia.org/wiki/GNU_General_Public_License#Linking_and_derived_works).

## CC BY 4.0

TODO (for fontawesome icons)

## SIL OFL 1.1

TODO (for fontawesome fonts)

## BSD-3-Clause

TOOD (for wavesurfer)

## Wider Legal Implications

### GDPR implications

TODO

### Music Copyright implications

TODO
