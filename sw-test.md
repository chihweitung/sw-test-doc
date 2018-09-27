Template
- Worker: 
- Description: 
- Related to: 
- Last changeset while updating: 

about-blank-replacement.https.html
- Worker: resources/about-blank-replacement-worker.js
- Description: This test attempts to verify various initial about:blank document creation is accurately reflected via the Clients API.
- Related to: #about:blank, #clients, #client
- Last changeset while updating: 398673

activate-event-after-install-state-change.https.html
- Worker: resources/empty-worker.js
- Description: A test ensures that the installed event should be fired before activating service worker
- Related to: #registration.installing, #registration.active, #sw.onstatechange, #sw.state
- Last changeset while updating: 292263

activation-after-registration.https.html
- Worker: resources/empty-worker.js
- Description: Worker should be in the "installing" state upon registration
- Related to: #registration.installing, #registration.active
- Last changeset while updating: 292263

activation.https.html
- Worker: resources/mint-new-worker.py
- Description: Test behaviors of a waiting worker, and an active worker with an inflight message.
- Related to: #postMessage, #registration.waiting, #registration.active
- Last changeset while updating: 418892

active.https.html
- Worker: resources/empty-worker.js
- Description: Test the values of a sw meet expectation.
- Related to: #registration.active, #container.controller, #registration.waiting, #registration.installing
- Last changeset while updating: 432057

appcache-ordering-main.https.html
- Worker: resources/empty-worker.js
- Description: serviceworkers take priority over appcaches
- Related to: ＃appcache
- Last changeset while updating: 296536

claim-affect-other-registration.https.html
- Worker: resources/empty.js, resources/claim-worker.js
- Description: claim() should affect the originally controlling registration
- Related to: #claim
- Last changeset while updating: 345327

claim-fetch.https.html
- Worker: resources/claim-worker.js
- Description: Test fetch() should be intercepted after the client is claimed
- Related to: #claim, #fetch
- Last changeset while updating: 369959

claim-not-using-registration.https.html
- Worker: resources/empty.js, resources/claim-worker.js
- Description: Test claim client which is not using registration and when there's a longer-matched registration
- Related to: #claim, #register
- Last changeset while updating: 354102

claim-shared-worker-fetch.https.html
- Worker: resources/claim-worker.js
- Description: fetch() in SharedWorker should be intercepted after the client is claimed
- Related to: #claim, #sharedworker, #fetch
- Last changeset while updating: 

claim-using-registration.https.html
- Worker: resources/empty.js, resources/claim-worker.js
- Description: Test worker claims client which is using the same or another registration
- Related to: #claim, #scope
- Last changeset while updating: 

claim-with-redirect.https.html
- Worker: resources/update-claim-worker.py
- Description: This test checks behavior when browser got a redirect header from in-scope page and navigated to out-of-scope page which has a different origin from any registrations.
- Related to: #claim, #redirect
- Last changeset while updating: 

claim-worker-fetch.https.html
- Worker: resources/claim-worker.js
- Description: fetch() in Worker or nested worker should be intercepted after the client is claimed
- Related to: #claim, #fetch
- Last changeset while updating:

client-id.https.html
- Worker: resources/client-id-worker.js
- Description: Check whether Client.id returns the client's ID
- Related to: #client.id
- Last changeset while updating: 

client-navigate.https.html
- Worker: client-navigate-worker.js
- Description: Check whether the frame location is accessable after successful/redirect/cross-origin/failed_about:blank/failed_mixed-content navigations
- Related to: #claim, #navigate
- Last changeset while updating:

clients-get-client-types.https.html
- Worker: resources/clients-get-client-types-worker.js
- Description: Test Clients.get() with window and worker clients
- Related to: #client
- Last changeset while updating: 

clients-get-cross-origin.https.html
- Worker: resources/clients-get-worker.js
- Description: This test asserts the behavior of the Client API in cases where the client belongs to a foreign origin. It does this by creating an iframe with a foreign origin which connects to a server worker in the current origin
- Related to: #client, #cross-origin
- Last changeset while updating: 

clients-get.https.html
- Worker: resources/clients-get-worker.js
- Description: Test Clients.get()
- Related to: #client.get
- Last changeset while updating: 

clients-matchall-client-types.https.html
- Worker: resources/clients-matchall-worker.js
- Description: Verify matchAll() with {window, sharedworker, worker} client types
- Related to: #client.matchAll
- Last changeset while updating: 

clients-matchall-exact-controller.https.html
- Worker: resources/clients-matchall-worker.js
- Description: Check client.matchAll for a sw in different state 
- Related to: #client.matchAll
- Last changeset while updating: 

clients-matchall-include-uncontrolled.https.html
- Worker: resources/clients-matchall-worker.js
- Description: [Not really sure this test] Run clients.matchAll without and with includeUncontrolled=true
- Related to: #client.matchAll #includeUncontrolled
- Last changeset while updating: 

clients-matchall-on-evaluation.https.html
- Worker: resources/clients-matchall-on-evaluation-worker.js
- Description: [Not really sure this test] Test clients.matchAll with includeUncontrolled=true
- Related to: #client.matchAll #includeUncontrolled
- Last changeset while updating: 

clients-matchall-order.https.html
- Worker: resources/clients-matchall-worker.js
- Description: Check the order of client by calling client.matchAll with the different options
- Related to: #client.matchAll
- Last changeset while updating: 

clients-matchall.https.html
- Worker: resources/clients-matchall-worker.js
- Description: Check whether does calling foucs() in a window client matter for client.matchAll
- Related to: #client.matchAll, #foucs
- Last changeset while updating: 

controller-on-disconnect.https.html
- Worker: resources/empty-worker.js
- Description: Verify controller is cleared on disconnected window
- Related to: #navigator.serviceWorker.controller
- Last changeset while updating: 

controller-on-load.https.html
- Worker: resources/empty-worker.js
- Description: Verify controller is set for a controlled document (objects from different windows should not be equal, but should be equal for the same windows)
- Related to: #navigator.serviceWorker.controller
- Last changeset while updating: 

controller-on-reload.https.html
- Worker: empty-worker.js
- Description: controller should be null until the document is reloaded, controller should be a ServiceWorker object upon reload
- Related to: #navigator.serviceWorker.controller, #reload
- Last changeset while updating: 

controller-with-no-fetch-event-handler.https.html
- Worker: resources/empty.js
- Description: Test a service worker if it doesn't handle fetch and the client does fetch
- Related to: #navigator.serviceWorker.controller, #fetch
- Last changeset while updating: 

dedicated-worker-service-worker-interception.https.html
- Worker: resources/service-worker-interception-service-worker.js
- Description: Top-level worker loading/Static import script/Dynamic import script should be intercepted by a service worker.
- Related to: #fetch, #dedicated-worker, #intercept
- Last changeset while updating: 

detached-context.https.html
- Worker: resources/empty-worker.js
- Description: Access ServiceWorkerRegistration/ServiceWorker_object/navigator.serviceWorker/navigator on a removed/detached/removed_about:blank frame
- Related to: #serviceWorker #registration, #about:blank
- Last changeset while updating: 

embed-and-object-are-not-intercepted.https.html
- Worker: resources/embed-and-object-are-not-intercepted-worker.js
- Description: Check EMBED or Object elements should be or shouldn't be intercepted by a service worker
- Related to: #intercept #HTML_element
- Last changeset while updating: 

extendable-event-async-waituntil.https.html
- Worker: resources/extendable-event-async-waituntil.js
- Description: Test calling waitUntil in different situations
- Related to: #waitUntil
- Last changeset while updating: 

extendable-event-waituntil.https.html
- Worker: resources/extendable-event-waituntil.js
- Description: Test lifetime Event with waitUnril
- Related to:  #waitUntil
- Last changeset while updating: 

fetch-canvas-tainting-image-cache.https.html
- Worker: resources/fetch-rewrite-worker.js
- Description: canvas tainting tests by using cached response
- Related to: #canvas, #fetch, #cross-origin, #tainting, #cache
- Last changeset while updating: 

fetch-canvas-tainting-image.https.html
- Worker: resources/fetch-rewrite-worker.js
- Description: anvas tainting tests 
- Related to: #canvas, #fetch, #cross-origin, #tainting
- Last changeset while updating: 

fetch-canvas-tainting-video-cache.https.html
- Worker: resources/fetch-rewrite-worker.js
- Description: canvas tainting tests by using cached response
- Related to: #canvas, #fetch, #cross-origin, #tainting, #cache, #video
- Last changeset while updating: 

- Worker: resources/fetch-rewrite-worker.js
- Description: 
- Related to: 
- Last changeset while updating: 

- Worker: 
- Description: 
- Related to: 
- Last changeset while updating: 

- Worker: 
- Description: 
- Related to: 
- Last changeset while updating: 

- Worker: 
- Description: 
- Related to: 
- Last changeset while updating: 

- Worker: 
- Description: 
- Related to: 
- Last changeset while updating: 

- Worker: 
- Description: 
- Related to: 
- Last changeset while updating: 

- Worker: 
- Description: 
- Related to: 
- Last changeset while updating: 

- Worker: 
- Description: 
- Related to: 
- Last changeset while updating: 

