# api documentation for  [react-dom (v15.5.3)](https://facebook.github.io/react/)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-dom.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-dom) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-dom.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-dom)
#### React package for working with the DOM.

[![NPM](https://nodei.co/npm/react-dom.png?downloads=true)](https://www.npmjs.com/package/react-dom)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-dom/build/screenCapture.buildNpmdoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-react-dom%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-dom/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-dom/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-dom/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browserify": {
        "transform": [
            "loose-envify"
        ]
    },
    "bugs": {
        "url": "https://github.com/facebook/react/issues"
    },
    "dependencies": {
        "fbjs": "^0.8.9",
        "loose-envify": "^1.1.0",
        "object-assign": "^4.1.0",
        "prop-types": "~15.5.0"
    },
    "description": "React package for working with the DOM.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "2ee127ce942df55da53111ae303316e68072b5c5",
        "tarball": "https://registry.npmjs.org/react-dom/-/react-dom-15.5.3.tgz"
    },
    "files": [
        "LICENSE",
        "PATENTS",
        "README.md",
        "dist/",
        "lib/",
        "index.js",
        "server.js",
        "test-utils.js"
    ],
    "homepage": "https://facebook.github.io/react/",
    "keywords": [
        "react"
    ],
    "license": "BSD-3-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "acdlite",
            "email": "acdlite@me.com"
        },
        {
            "name": "brianvaughn",
            "email": "briandavidvaughn@gmail.com"
        },
        {
            "name": "fb",
            "email": "opensource+npm@fb.com"
        },
        {
            "name": "gaearon",
            "email": "dan.abramov@gmail.com"
        },
        {
            "name": "sebmarkbage",
            "email": "sebastian@calyptus.eu"
        },
        {
            "name": "spicyj",
            "email": "ben@benalpert.com"
        },
        {
            "name": "tomocchino",
            "email": "tomocchino@gmail.com"
        },
        {
            "name": "trueadm",
            "email": "dg@domgan.com"
        },
        {
            "name": "zpao",
            "email": "paul@oshannessy.com"
        }
    ],
    "name": "react-dom",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^15.5.3"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/facebook/react.git"
    },
    "scripts": {
        "start": "node server.js"
    },
    "version": "15.5.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react-dom](#apidoc.module.react-dom)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>CallbackQueue (arg)](#apidoc.element.react-dom.CallbackQueue)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>DOMLazyTree (node)](#apidoc.element.react-dom.DOMLazyTree)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>FallbackCompositionState (root)](#apidoc.element.react-dom.FallbackCompositionState)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ReactDOMComponent (element)](#apidoc.element.react-dom.ReactDOMComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ReactDOMEmptyComponent (instantiate)](#apidoc.element.react-dom.ReactDOMEmptyComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ReactDOMTextComponent (text)](#apidoc.element.react-dom.ReactDOMTextComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ReactReconcileTransaction (useCreateElement)](#apidoc.element.react-dom.ReactReconcileTransaction)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ReactServerRenderingTransaction (renderToStaticMarkup)](#apidoc.element.react-dom.ReactServerRenderingTransaction)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ReactServerUpdateQueue (transaction)](#apidoc.element.react-dom.ReactServerUpdateQueue)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ReactShallowRenderer ()](#apidoc.element.react-dom.ReactShallowRenderer)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ReactSimpleEmptyComponent (placeholderElement, instantiate)](#apidoc.element.react-dom.ReactSimpleEmptyComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ReactTestReconcileTransaction (testOptions)](#apidoc.element.react-dom.ReactTestReconcileTransaction)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ResponderSyntheticEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.ResponderSyntheticEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticAnimationEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticAnimationEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticClipboardEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticClipboardEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticCompositionEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticCompositionEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticDragEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticDragEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticEvent {{signature}}](#apidoc.element.react-dom.SyntheticEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticFocusEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticFocusEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticInputEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticInputEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticKeyboardEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticKeyboardEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticMouseEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticMouseEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticTouchEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticTouchEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticTransitionEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticTransitionEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticUIEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticUIEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticWheelEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticWheelEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>findDOMNode (componentOrElement)](#apidoc.element.react-dom.findDOMNode)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>render (nextElement, container, callback)](#apidoc.element.react-dom.render)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>unmountComponentAtNode (container)](#apidoc.element.react-dom.unmountComponentAtNode)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>unstable_batchedUpdates (callback, a, b, c, d, e)](#apidoc.element.react-dom.unstable_batchedUpdates)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>unstable_renderSubtreeIntoContainer (parentComponent, nextElement, container, callback)](#apidoc.element.react-dom.unstable_renderSubtreeIntoContainer)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>validateDOMNesting (childTag, childText, childInstance, ancestorInfo)](#apidoc.element.react-dom.validateDOMNesting)
1.  object <span class="apidocSignatureSpan">react-dom.</span>AutoFocusUtils
1.  object <span class="apidocSignatureSpan">react-dom.</span>BeforeInputEventPlugin
1.  object <span class="apidocSignatureSpan">react-dom.</span>CSSPropertyOperations
1.  object <span class="apidocSignatureSpan">react-dom.</span>CallbackQueue.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>ChangeEventPlugin
1.  object <span class="apidocSignatureSpan">react-dom.</span>DOMChildrenOperations
1.  object <span class="apidocSignatureSpan">react-dom.</span>DOMProperty
1.  object <span class="apidocSignatureSpan">react-dom.</span>DOMPropertyOperations
1.  object <span class="apidocSignatureSpan">react-dom.</span>Danger
1.  object <span class="apidocSignatureSpan">react-dom.</span>EnterLeaveEventPlugin
1.  object <span class="apidocSignatureSpan">react-dom.</span>EventPluginHub
1.  object <span class="apidocSignatureSpan">react-dom.</span>EventPluginRegistry
1.  object <span class="apidocSignatureSpan">react-dom.</span>EventPluginUtils
1.  object <span class="apidocSignatureSpan">react-dom.</span>EventPropagators
1.  object <span class="apidocSignatureSpan">react-dom.</span>FallbackCompositionState.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>HTMLDOMPropertyConfig
1.  object <span class="apidocSignatureSpan">react-dom.</span>KeyEscapeUtils
1.  object <span class="apidocSignatureSpan">react-dom.</span>LinkedValueUtils
1.  object <span class="apidocSignatureSpan">react-dom.</span>PooledClass
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactBrowserEventEmitter
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactChildFiber
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactChildReconciler
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactComponentBrowserEnvironment
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactComponentEnvironment
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactComponentTreeTestUtils
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactCompositeComponent
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactCoroutine
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactDOMComponent.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactDOMComponentTree
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactDOMEmptyComponent.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactDOMIDOperations
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactDOMInput
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactDOMInvalidARIAHook
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactDOMNullInputValuePropHook
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactDOMOption
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactDOMSelect
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactDOMSelection
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactDOMServer
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactDOMTextComponent.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactDOMTextarea
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactDOMTreeTraversal
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactDOMUnknownPropertyHook
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactDebugTool
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactDefaultBatchingStrategy
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactDefaultInjection
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactEmptyComponent
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactErrorUtils
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactEventEmitterMixin
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactEventListener
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactFiber
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactFiberRoot
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactFiberUpdateQueue
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactHostComponent
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactHostOperationHistoryHook
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactInputSelection
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactInstanceMap
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactInvalidSetStateWarningHook
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactMarkupChecksum
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactMount
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactNodeTypes
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactOwner
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactPerf
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactReconcileTransaction.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactReconciler
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactRef
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactReifiedYield
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactServerBatchingStrategy
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactServerRendering
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactServerRenderingTransaction.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactServerUpdateQueue.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactShallowRenderer.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactSimpleEmptyComponent.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactTestReconcileTransaction.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactTestUtils
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactUpdateQueue
1.  object <span class="apidocSignatureSpan">react-dom.</span>ReactUpdates
1.  object <span class="apidocSignatureSpan">react-dom.</span>ResponderEventPlugin
1.  object <span class="apidocSignatureSpan">react-dom.</span>ResponderSyntheticEvent.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>ResponderTouchHistoryStore
1.  object <span class="apidocSignatureSpan">react-dom.</span>SelectEventPlugin
1.  object <span class="apidocSignatureSpan">react-dom.</span>SimpleEventPlugin
1.  object <span class="apidocSignatureSpan">react-dom.</span>SyntheticAnimationEvent.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>SyntheticClipboardEvent.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>SyntheticCompositionEvent.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>SyntheticDragEvent.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>SyntheticEvent.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>SyntheticFocusEvent.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>SyntheticInputEvent.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>SyntheticKeyboardEvent.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>SyntheticMouseEvent.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>SyntheticTouchEvent.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>SyntheticTransitionEvent.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>SyntheticUIEvent.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>SyntheticWheelEvent.prototype
1.  object <span class="apidocSignatureSpan">react-dom.</span>TapEventPlugin
1.  object <span class="apidocSignatureSpan">react-dom.</span>TouchHistoryMath
1.  object <span class="apidocSignatureSpan">react-dom.</span>Transaction
1.  object <span class="apidocSignatureSpan">react-dom.</span>ViewportMetrics
1.  object <span class="apidocSignatureSpan">react-dom.</span>__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED
1.  string <span class="apidocSignatureSpan">react-dom.</span>version

#### [module react-dom.AutoFocusUtils](#apidoc.module.react-dom.AutoFocusUtils)
1.  [function <span class="apidocSignatureSpan">react-dom.AutoFocusUtils.</span>focusDOMComponent ()](#apidoc.element.react-dom.AutoFocusUtils.focusDOMComponent)

#### [module react-dom.BeforeInputEventPlugin](#apidoc.module.react-dom.BeforeInputEventPlugin)
1.  [function <span class="apidocSignatureSpan">react-dom.BeforeInputEventPlugin.</span>extractEvents (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.BeforeInputEventPlugin.extractEvents)
1.  object <span class="apidocSignatureSpan">react-dom.BeforeInputEventPlugin.</span>eventTypes

#### [module react-dom.CSSPropertyOperations](#apidoc.module.react-dom.CSSPropertyOperations)
1.  [function <span class="apidocSignatureSpan">react-dom.CSSPropertyOperations.</span>createMarkupForStyles (styles, component)](#apidoc.element.react-dom.CSSPropertyOperations.createMarkupForStyles)
1.  [function <span class="apidocSignatureSpan">react-dom.CSSPropertyOperations.</span>setValueForStyles (node, styles, component)](#apidoc.element.react-dom.CSSPropertyOperations.setValueForStyles)

#### [module react-dom.CallbackQueue](#apidoc.module.react-dom.CallbackQueue)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>CallbackQueue (arg)](#apidoc.element.react-dom.CallbackQueue.CallbackQueue)
1.  [function <span class="apidocSignatureSpan">react-dom.CallbackQueue.</span>getPooled (copyFieldsFrom)](#apidoc.element.react-dom.CallbackQueue.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.CallbackQueue.</span>release (instance)](#apidoc.element.react-dom.CallbackQueue.release)
1.  number <span class="apidocSignatureSpan">react-dom.CallbackQueue.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.CallbackQueue.</span>instancePool

#### [module react-dom.CallbackQueue.prototype](#apidoc.module.react-dom.CallbackQueue.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.CallbackQueue.prototype.</span>checkpoint ()](#apidoc.element.react-dom.CallbackQueue.prototype.checkpoint)
1.  [function <span class="apidocSignatureSpan">react-dom.CallbackQueue.prototype.</span>destructor ()](#apidoc.element.react-dom.CallbackQueue.prototype.destructor)
1.  [function <span class="apidocSignatureSpan">react-dom.CallbackQueue.prototype.</span>enqueue (callback, context)](#apidoc.element.react-dom.CallbackQueue.prototype.enqueue)
1.  [function <span class="apidocSignatureSpan">react-dom.CallbackQueue.prototype.</span>notifyAll ()](#apidoc.element.react-dom.CallbackQueue.prototype.notifyAll)
1.  [function <span class="apidocSignatureSpan">react-dom.CallbackQueue.prototype.</span>reset ()](#apidoc.element.react-dom.CallbackQueue.prototype.reset)
1.  [function <span class="apidocSignatureSpan">react-dom.CallbackQueue.prototype.</span>rollback (len)](#apidoc.element.react-dom.CallbackQueue.prototype.rollback)

#### [module react-dom.ChangeEventPlugin](#apidoc.module.react-dom.ChangeEventPlugin)
1.  [function <span class="apidocSignatureSpan">react-dom.ChangeEventPlugin.</span>extractEvents (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.ChangeEventPlugin.extractEvents)
1.  object <span class="apidocSignatureSpan">react-dom.ChangeEventPlugin.</span>eventTypes

#### [module react-dom.DOMChildrenOperations](#apidoc.module.react-dom.DOMChildrenOperations)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMChildrenOperations.</span>dangerouslyReplaceNodeWithMarkup (oldChild, markup, prevInstance)](#apidoc.element.react-dom.DOMChildrenOperations.dangerouslyReplaceNodeWithMarkup)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMChildrenOperations.</span>processUpdates (parentNode, updates)](#apidoc.element.react-dom.DOMChildrenOperations.processUpdates)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMChildrenOperations.</span>replaceDelimitedText (openingComment, closingComment, stringText)](#apidoc.element.react-dom.DOMChildrenOperations.replaceDelimitedText)

#### [module react-dom.DOMLazyTree](#apidoc.module.react-dom.DOMLazyTree)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>DOMLazyTree (node)](#apidoc.element.react-dom.DOMLazyTree.DOMLazyTree)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMLazyTree.</span>insertTreeBefore (parentNode, tree, referenceNode)](#apidoc.element.react-dom.DOMLazyTree.insertTreeBefore)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMLazyTree.</span>queueChild (parentTree, childTree)](#apidoc.element.react-dom.DOMLazyTree.queueChild)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMLazyTree.</span>queueHTML (tree, html)](#apidoc.element.react-dom.DOMLazyTree.queueHTML)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMLazyTree.</span>queueText (tree, text)](#apidoc.element.react-dom.DOMLazyTree.queueText)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMLazyTree.</span>replaceChildWithTree (oldNode, newTree)](#apidoc.element.react-dom.DOMLazyTree.replaceChildWithTree)

#### [module react-dom.DOMProperty](#apidoc.module.react-dom.DOMProperty)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMProperty.</span>isCustomAttribute (attributeName)](#apidoc.element.react-dom.DOMProperty.isCustomAttribute)
1.  object <span class="apidocSignatureSpan">react-dom.DOMProperty.</span>_isCustomAttributeFunctions
1.  object <span class="apidocSignatureSpan">react-dom.DOMProperty.</span>getPossibleStandardName
1.  object <span class="apidocSignatureSpan">react-dom.DOMProperty.</span>injection
1.  object <span class="apidocSignatureSpan">react-dom.DOMProperty.</span>properties
1.  string <span class="apidocSignatureSpan">react-dom.DOMProperty.</span>ATTRIBUTE_NAME_CHAR
1.  string <span class="apidocSignatureSpan">react-dom.DOMProperty.</span>ATTRIBUTE_NAME_START_CHAR
1.  string <span class="apidocSignatureSpan">react-dom.DOMProperty.</span>ID_ATTRIBUTE_NAME
1.  string <span class="apidocSignatureSpan">react-dom.DOMProperty.</span>ROOT_ATTRIBUTE_NAME

#### [module react-dom.DOMPropertyOperations](#apidoc.module.react-dom.DOMPropertyOperations)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>createMarkupForCustomAttribute (name, value)](#apidoc.element.react-dom.DOMPropertyOperations.createMarkupForCustomAttribute)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>createMarkupForID (id)](#apidoc.element.react-dom.DOMPropertyOperations.createMarkupForID)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>createMarkupForProperty (name, value)](#apidoc.element.react-dom.DOMPropertyOperations.createMarkupForProperty)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>createMarkupForRoot ()](#apidoc.element.react-dom.DOMPropertyOperations.createMarkupForRoot)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>deleteValueForAttribute (node, name)](#apidoc.element.react-dom.DOMPropertyOperations.deleteValueForAttribute)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>deleteValueForProperty (node, name)](#apidoc.element.react-dom.DOMPropertyOperations.deleteValueForProperty)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>setAttributeForID (node, id)](#apidoc.element.react-dom.DOMPropertyOperations.setAttributeForID)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>setAttributeForRoot (node)](#apidoc.element.react-dom.DOMPropertyOperations.setAttributeForRoot)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>setValueForAttribute (node, name, value)](#apidoc.element.react-dom.DOMPropertyOperations.setValueForAttribute)
1.  [function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>setValueForProperty (node, name, value)](#apidoc.element.react-dom.DOMPropertyOperations.setValueForProperty)

#### [module react-dom.Danger](#apidoc.module.react-dom.Danger)
1.  [function <span class="apidocSignatureSpan">react-dom.Danger.</span>dangerouslyReplaceNodeWithMarkup (oldChild, markup)](#apidoc.element.react-dom.Danger.dangerouslyReplaceNodeWithMarkup)

#### [module react-dom.EnterLeaveEventPlugin](#apidoc.module.react-dom.EnterLeaveEventPlugin)
1.  [function <span class="apidocSignatureSpan">react-dom.EnterLeaveEventPlugin.</span>extractEvents (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.EnterLeaveEventPlugin.extractEvents)
1.  object <span class="apidocSignatureSpan">react-dom.EnterLeaveEventPlugin.</span>eventTypes

#### [module react-dom.EventPluginHub](#apidoc.module.react-dom.EventPluginHub)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>__getListenerBank ()](#apidoc.element.react-dom.EventPluginHub.__getListenerBank)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>__purge ()](#apidoc.element.react-dom.EventPluginHub.__purge)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>deleteAllListeners (inst)](#apidoc.element.react-dom.EventPluginHub.deleteAllListeners)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>deleteListener (inst, registrationName)](#apidoc.element.react-dom.EventPluginHub.deleteListener)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>enqueueEvents (events)](#apidoc.element.react-dom.EventPluginHub.enqueueEvents)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>extractEvents (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.EventPluginHub.extractEvents)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>getListener (inst, registrationName)](#apidoc.element.react-dom.EventPluginHub.getListener)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>processEventQueue (simulated)](#apidoc.element.react-dom.EventPluginHub.processEventQueue)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>putListener (inst, registrationName, listener)](#apidoc.element.react-dom.EventPluginHub.putListener)
1.  object <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>injection

#### [module react-dom.EventPluginRegistry](#apidoc.module.react-dom.EventPluginRegistry)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginRegistry.</span>_resetEventPlugins ()](#apidoc.element.react-dom.EventPluginRegistry._resetEventPlugins)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginRegistry.</span>getPluginModuleForEvent (event)](#apidoc.element.react-dom.EventPluginRegistry.getPluginModuleForEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginRegistry.</span>injectEventPluginOrder (injectedEventPluginOrder)](#apidoc.element.react-dom.EventPluginRegistry.injectEventPluginOrder)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginRegistry.</span>injectEventPluginsByName (injectedNamesToPlugins)](#apidoc.element.react-dom.EventPluginRegistry.injectEventPluginsByName)
1.  object <span class="apidocSignatureSpan">react-dom.EventPluginRegistry.</span>eventNameDispatchConfigs
1.  object <span class="apidocSignatureSpan">react-dom.EventPluginRegistry.</span>plugins
1.  object <span class="apidocSignatureSpan">react-dom.EventPluginRegistry.</span>possibleRegistrationNames
1.  object <span class="apidocSignatureSpan">react-dom.EventPluginRegistry.</span>registrationNameDependencies
1.  object <span class="apidocSignatureSpan">react-dom.EventPluginRegistry.</span>registrationNameModules

#### [module react-dom.EventPluginUtils](#apidoc.module.react-dom.EventPluginUtils)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>executeDirectDispatch (event)](#apidoc.element.react-dom.EventPluginUtils.executeDirectDispatch)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>executeDispatchesInOrder (event, simulated)](#apidoc.element.react-dom.EventPluginUtils.executeDispatchesInOrder)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>executeDispatchesInOrderStopAtTrue (event)](#apidoc.element.react-dom.EventPluginUtils.executeDispatchesInOrderStopAtTrue)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>getInstanceFromNode (node)](#apidoc.element.react-dom.EventPluginUtils.getInstanceFromNode)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>getLowestCommonAncestor (a, b)](#apidoc.element.react-dom.EventPluginUtils.getLowestCommonAncestor)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>getNodeFromInstance (node)](#apidoc.element.react-dom.EventPluginUtils.getNodeFromInstance)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>getParentInstance (inst)](#apidoc.element.react-dom.EventPluginUtils.getParentInstance)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>hasDispatches (event)](#apidoc.element.react-dom.EventPluginUtils.hasDispatches)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>isAncestor (a, b)](#apidoc.element.react-dom.EventPluginUtils.isAncestor)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>isEndish (topLevelType)](#apidoc.element.react-dom.EventPluginUtils.isEndish)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>isMoveish (topLevelType)](#apidoc.element.react-dom.EventPluginUtils.isMoveish)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>isStartish (topLevelType)](#apidoc.element.react-dom.EventPluginUtils.isStartish)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>traverseEnterLeave (from, to, fn, argFrom, argTo)](#apidoc.element.react-dom.EventPluginUtils.traverseEnterLeave)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>traverseTwoPhase (target, fn, arg)](#apidoc.element.react-dom.EventPluginUtils.traverseTwoPhase)
1.  object <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>injection

#### [module react-dom.EventPropagators](#apidoc.module.react-dom.EventPropagators)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPropagators.</span>accumulateDirectDispatches (events)](#apidoc.element.react-dom.EventPropagators.accumulateDirectDispatches)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPropagators.</span>accumulateEnterLeaveDispatches (leave, enter, from, to)](#apidoc.element.react-dom.EventPropagators.accumulateEnterLeaveDispatches)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPropagators.</span>accumulateTwoPhaseDispatches (events)](#apidoc.element.react-dom.EventPropagators.accumulateTwoPhaseDispatches)
1.  [function <span class="apidocSignatureSpan">react-dom.EventPropagators.</span>accumulateTwoPhaseDispatchesSkipTarget (events)](#apidoc.element.react-dom.EventPropagators.accumulateTwoPhaseDispatchesSkipTarget)

#### [module react-dom.FallbackCompositionState](#apidoc.module.react-dom.FallbackCompositionState)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>FallbackCompositionState (root)](#apidoc.element.react-dom.FallbackCompositionState.FallbackCompositionState)
1.  [function <span class="apidocSignatureSpan">react-dom.FallbackCompositionState.</span>getPooled (copyFieldsFrom)](#apidoc.element.react-dom.FallbackCompositionState.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.FallbackCompositionState.</span>release (instance)](#apidoc.element.react-dom.FallbackCompositionState.release)
1.  number <span class="apidocSignatureSpan">react-dom.FallbackCompositionState.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.FallbackCompositionState.</span>instancePool

#### [module react-dom.FallbackCompositionState.prototype](#apidoc.module.react-dom.FallbackCompositionState.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.FallbackCompositionState.prototype.</span>destructor ()](#apidoc.element.react-dom.FallbackCompositionState.prototype.destructor)
1.  [function <span class="apidocSignatureSpan">react-dom.FallbackCompositionState.prototype.</span>getData ()](#apidoc.element.react-dom.FallbackCompositionState.prototype.getData)
1.  [function <span class="apidocSignatureSpan">react-dom.FallbackCompositionState.prototype.</span>getText ()](#apidoc.element.react-dom.FallbackCompositionState.prototype.getText)

#### [module react-dom.HTMLDOMPropertyConfig](#apidoc.module.react-dom.HTMLDOMPropertyConfig)
1.  [function <span class="apidocSignatureSpan">react-dom.HTMLDOMPropertyConfig.</span>isCustomAttribute ()](#apidoc.element.react-dom.HTMLDOMPropertyConfig.isCustomAttribute)
1.  object <span class="apidocSignatureSpan">react-dom.HTMLDOMPropertyConfig.</span>DOMAttributeNames
1.  object <span class="apidocSignatureSpan">react-dom.HTMLDOMPropertyConfig.</span>DOMMutationMethods
1.  object <span class="apidocSignatureSpan">react-dom.HTMLDOMPropertyConfig.</span>DOMPropertyNames
1.  object <span class="apidocSignatureSpan">react-dom.HTMLDOMPropertyConfig.</span>Properties

#### [module react-dom.KeyEscapeUtils](#apidoc.module.react-dom.KeyEscapeUtils)
1.  [function <span class="apidocSignatureSpan">react-dom.KeyEscapeUtils.</span>escape (key)](#apidoc.element.react-dom.KeyEscapeUtils.escape)
1.  [function <span class="apidocSignatureSpan">react-dom.KeyEscapeUtils.</span>unescape (key)](#apidoc.element.react-dom.KeyEscapeUtils.unescape)

#### [module react-dom.LinkedValueUtils](#apidoc.module.react-dom.LinkedValueUtils)
1.  [function <span class="apidocSignatureSpan">react-dom.LinkedValueUtils.</span>checkPropTypes (tagName, props, owner)](#apidoc.element.react-dom.LinkedValueUtils.checkPropTypes)
1.  [function <span class="apidocSignatureSpan">react-dom.LinkedValueUtils.</span>executeOnChange (inputProps, event)](#apidoc.element.react-dom.LinkedValueUtils.executeOnChange)
1.  [function <span class="apidocSignatureSpan">react-dom.LinkedValueUtils.</span>getChecked (inputProps)](#apidoc.element.react-dom.LinkedValueUtils.getChecked)
1.  [function <span class="apidocSignatureSpan">react-dom.LinkedValueUtils.</span>getValue (inputProps)](#apidoc.element.react-dom.LinkedValueUtils.getValue)

#### [module react-dom.PooledClass](#apidoc.module.react-dom.PooledClass)
1.  [function <span class="apidocSignatureSpan">react-dom.PooledClass.</span>addPoolingTo (CopyConstructor, pooler)](#apidoc.element.react-dom.PooledClass.addPoolingTo)
1.  [function <span class="apidocSignatureSpan">react-dom.PooledClass.</span>fourArgumentPooler (a1, a2, a3, a4)](#apidoc.element.react-dom.PooledClass.fourArgumentPooler)
1.  [function <span class="apidocSignatureSpan">react-dom.PooledClass.</span>oneArgumentPooler (copyFieldsFrom)](#apidoc.element.react-dom.PooledClass.oneArgumentPooler)
1.  [function <span class="apidocSignatureSpan">react-dom.PooledClass.</span>threeArgumentPooler (a1, a2, a3)](#apidoc.element.react-dom.PooledClass.threeArgumentPooler)
1.  [function <span class="apidocSignatureSpan">react-dom.PooledClass.</span>twoArgumentPooler (a1, a2)](#apidoc.element.react-dom.PooledClass.twoArgumentPooler)

#### [module react-dom.ReactBrowserEventEmitter](#apidoc.module.react-dom.ReactBrowserEventEmitter)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactBrowserEventEmitter.</span>ensureScrollValueMonitoring ()](#apidoc.element.react-dom.ReactBrowserEventEmitter.ensureScrollValueMonitoring)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactBrowserEventEmitter.</span>handleTopLevel (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.ReactBrowserEventEmitter.handleTopLevel)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactBrowserEventEmitter.</span>isEnabled ()](#apidoc.element.react-dom.ReactBrowserEventEmitter.isEnabled)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactBrowserEventEmitter.</span>listenTo (registrationName, contentDocumentHandle)](#apidoc.element.react-dom.ReactBrowserEventEmitter.listenTo)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactBrowserEventEmitter.</span>setEnabled (enabled)](#apidoc.element.react-dom.ReactBrowserEventEmitter.setEnabled)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactBrowserEventEmitter.</span>supportsEventPageXY ()](#apidoc.element.react-dom.ReactBrowserEventEmitter.supportsEventPageXY)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactBrowserEventEmitter.</span>trapBubbledEvent (topLevelType, handlerBaseName, handle)](#apidoc.element.react-dom.ReactBrowserEventEmitter.trapBubbledEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactBrowserEventEmitter.</span>trapCapturedEvent (topLevelType, handlerBaseName, handle)](#apidoc.element.react-dom.ReactBrowserEventEmitter.trapCapturedEvent)
1.  object <span class="apidocSignatureSpan">react-dom.ReactBrowserEventEmitter.</span>ReactEventListener
1.  object <span class="apidocSignatureSpan">react-dom.ReactBrowserEventEmitter.</span>injection

#### [module react-dom.ReactChildFiber](#apidoc.module.react-dom.ReactChildFiber)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactChildFiber.</span>cloneChildFibers (current, workInProgress)](#apidoc.element.react-dom.ReactChildFiber.cloneChildFibers)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactChildFiber.</span>reconcileChildFibers (returnFiber, currentFirstChild, newChildren, priority)](#apidoc.element.react-dom.ReactChildFiber.reconcileChildFibers)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactChildFiber.</span>reconcileChildFibersInPlace (returnFiber, currentFirstChild, newChildren, priority)](#apidoc.element.react-dom.ReactChildFiber.reconcileChildFibersInPlace)

#### [module react-dom.ReactChildReconciler](#apidoc.module.react-dom.ReactChildReconciler)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactChildReconciler.</span>instantiateChildren (nestedChildNodes, transaction, context, selfDebugID // 0 in production and for roots )](#apidoc.element.react-dom.ReactChildReconciler.instantiateChildren)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactChildReconciler.</span>unmountChildren (renderedChildren, safely)](#apidoc.element.react-dom.ReactChildReconciler.unmountChildren)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactChildReconciler.</span>updateChildren (prevChildren, nextChildren, mountImages, removedNodes, transaction, hostParent, hostContainerInfo, context, selfDebugID // 0 in production and for roots )](#apidoc.element.react-dom.ReactChildReconciler.updateChildren)

#### [module react-dom.ReactComponentBrowserEnvironment](#apidoc.module.react-dom.ReactComponentBrowserEnvironment)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactComponentBrowserEnvironment.</span>processChildrenUpdates (parentInst, updates)](#apidoc.element.react-dom.ReactComponentBrowserEnvironment.processChildrenUpdates)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactComponentBrowserEnvironment.</span>replaceNodeWithMarkup (oldChild, markup, prevInstance)](#apidoc.element.react-dom.ReactComponentBrowserEnvironment.replaceNodeWithMarkup)

#### [module react-dom.ReactComponentEnvironment](#apidoc.module.react-dom.ReactComponentEnvironment)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactComponentEnvironment.</span>processChildrenUpdates (parentInst, updates)](#apidoc.element.react-dom.ReactComponentEnvironment.processChildrenUpdates)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactComponentEnvironment.</span>replaceNodeWithMarkup (oldChild, markup, prevInstance)](#apidoc.element.react-dom.ReactComponentEnvironment.replaceNodeWithMarkup)
1.  object <span class="apidocSignatureSpan">react-dom.ReactComponentEnvironment.</span>injection

#### [module react-dom.ReactComponentTreeTestUtils](#apidoc.module.react-dom.ReactComponentTreeTestUtils)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactComponentTreeTestUtils.</span>expectTree (rootID, expectedTree, parentPath)](#apidoc.element.react-dom.ReactComponentTreeTestUtils.expectTree)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactComponentTreeTestUtils.</span>getRegisteredDisplayNames ()](#apidoc.element.react-dom.ReactComponentTreeTestUtils.getRegisteredDisplayNames)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactComponentTreeTestUtils.</span>getRootDisplayNames ()](#apidoc.element.react-dom.ReactComponentTreeTestUtils.getRootDisplayNames)

#### [module react-dom.ReactCompositeComponent](#apidoc.module.react-dom.ReactCompositeComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_checkContextTypes (typeSpecs, values, location)](#apidoc.element.react-dom.ReactCompositeComponent._checkContextTypes)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_constructComponent (doConstruct, publicProps, publicContext, updateQueue)](#apidoc.element.react-dom.ReactCompositeComponent._constructComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_constructComponentWithoutOwner (doConstruct, publicProps, publicContext, updateQueue)](#apidoc.element.react-dom.ReactCompositeComponent._constructComponentWithoutOwner)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_maskContext (context)](#apidoc.element.react-dom.ReactCompositeComponent._maskContext)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_performComponentUpdate (nextElement, nextProps, nextState, nextContext, transaction, unmaskedContext)](#apidoc.element.react-dom.ReactCompositeComponent._performComponentUpdate)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_processChildContext (currentContext)](#apidoc.element.react-dom.ReactCompositeComponent._processChildContext)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_processContext (context)](#apidoc.element.react-dom.ReactCompositeComponent._processContext)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_processPendingState (props, context)](#apidoc.element.react-dom.ReactCompositeComponent._processPendingState)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_renderValidatedComponent ()](#apidoc.element.react-dom.ReactCompositeComponent._renderValidatedComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_renderValidatedComponentWithoutOwnerOrContext ()](#apidoc.element.react-dom.ReactCompositeComponent._renderValidatedComponentWithoutOwnerOrContext)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_replaceNodeWithMarkup (oldHostNode, nextMarkup, prevInstance)](#apidoc.element.react-dom.ReactCompositeComponent._replaceNodeWithMarkup)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_updateRenderedComponent (transaction, context)](#apidoc.element.react-dom.ReactCompositeComponent._updateRenderedComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>attachRef (ref, component)](#apidoc.element.react-dom.ReactCompositeComponent.attachRef)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>construct (element)](#apidoc.element.react-dom.ReactCompositeComponent.construct)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>detachRef (ref)](#apidoc.element.react-dom.ReactCompositeComponent.detachRef)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>getHostNode ()](#apidoc.element.react-dom.ReactCompositeComponent.getHostNode)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>getName ()](#apidoc.element.react-dom.ReactCompositeComponent.getName)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>getPublicInstance ()](#apidoc.element.react-dom.ReactCompositeComponent.getPublicInstance)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>mountComponent (transaction, hostParent, hostContainerInfo, context)](#apidoc.element.react-dom.ReactCompositeComponent.mountComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>performInitialMount (renderedElement, hostParent, hostContainerInfo, transaction, context)](#apidoc.element.react-dom.ReactCompositeComponent.performInitialMount)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>performInitialMountWithErrorHandling (renderedElement, hostParent, hostContainerInfo, transaction, context)](#apidoc.element.react-dom.ReactCompositeComponent.performInitialMountWithErrorHandling)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>performUpdateIfNecessary (transaction)](#apidoc.element.react-dom.ReactCompositeComponent.performUpdateIfNecessary)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>receiveComponent (nextElement, transaction, nextContext)](#apidoc.element.react-dom.ReactCompositeComponent.receiveComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>unmountComponent (safely)](#apidoc.element.react-dom.ReactCompositeComponent.unmountComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>updateComponent (transaction, prevParentElement, nextParentElement, prevUnmaskedContext, nextUnmaskedContext)](#apidoc.element.react-dom.ReactCompositeComponent.updateComponent)
1.  object <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_instantiateReactComponent

#### [module react-dom.ReactCoroutine](#apidoc.module.react-dom.ReactCoroutine)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCoroutine.</span>createCoroutine (children, handler, props)](#apidoc.element.react-dom.ReactCoroutine.createCoroutine)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCoroutine.</span>createYield (props, continuation)](#apidoc.element.react-dom.ReactCoroutine.createYield)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCoroutine.</span>isCoroutine (object)](#apidoc.element.react-dom.ReactCoroutine.isCoroutine)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactCoroutine.</span>isYield (object)](#apidoc.element.react-dom.ReactCoroutine.isYield)
1.  symbol <span class="apidocSignatureSpan">react-dom.ReactCoroutine.</span>REACT_COROUTINE_TYPE
1.  symbol <span class="apidocSignatureSpan">react-dom.ReactCoroutine.</span>REACT_YIELD_TYPE

#### [module react-dom.ReactDOMComponent](#apidoc.module.react-dom.ReactDOMComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ReactDOMComponent (element)](#apidoc.element.react-dom.ReactDOMComponent.ReactDOMComponent)
1.  object <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.</span>Mixin
1.  string <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.</span>displayName

#### [module react-dom.ReactDOMComponent.prototype](#apidoc.module.react-dom.ReactDOMComponent.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_createContentMarkup (transaction, props, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype._createContentMarkup)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_createInitialChildren (transaction, props, context, lazyTree)](#apidoc.element.react-dom.ReactDOMComponent.prototype._createInitialChildren)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_createOpenTagMarkupAndPutListeners (transaction, props)](#apidoc.element.react-dom.ReactDOMComponent.prototype._createOpenTagMarkupAndPutListeners)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_mountChildAtIndex (child, mountImage, afterNode, index, transaction, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype._mountChildAtIndex)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_reconcilerInstantiateChildren (nestedChildren, transaction, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype._reconcilerInstantiateChildren)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_reconcilerUpdateChildren (prevChildren, nextNestedChildrenElements, mountImages, removedNodes, transaction, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype._reconcilerUpdateChildren)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_unmountChild (child, node)](#apidoc.element.react-dom.ReactDOMComponent.prototype._unmountChild)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_updateChildren (nextNestedChildrenElements, transaction, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype._updateChildren)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_updateDOMChildren (lastProps, nextProps, transaction, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype._updateDOMChildren)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_updateDOMProperties (lastProps, nextProps, transaction)](#apidoc.element.react-dom.ReactDOMComponent.prototype._updateDOMProperties)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>createChild (child, afterNode, mountImage)](#apidoc.element.react-dom.ReactDOMComponent.prototype.createChild)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>getHostNode ()](#apidoc.element.react-dom.ReactDOMComponent.prototype.getHostNode)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>getPublicInstance ()](#apidoc.element.react-dom.ReactDOMComponent.prototype.getPublicInstance)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>mountChildren (nestedChildren, transaction, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype.mountChildren)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>mountComponent (transaction, hostParent, hostContainerInfo, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype.mountComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>moveChild (child, afterNode, toIndex, lastIndex)](#apidoc.element.react-dom.ReactDOMComponent.prototype.moveChild)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>receiveComponent (nextElement, transaction, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype.receiveComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>removeChild (child, node)](#apidoc.element.react-dom.ReactDOMComponent.prototype.removeChild)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>unmountChildren (safely)](#apidoc.element.react-dom.ReactDOMComponent.prototype.unmountChildren)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>unmountComponent (safely)](#apidoc.element.react-dom.ReactDOMComponent.prototype.unmountComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>updateChildren (nextNestedChildrenElements, transaction, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype.updateChildren)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>updateComponent (transaction, prevElement, nextElement, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype.updateComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>updateMarkup (nextMarkup)](#apidoc.element.react-dom.ReactDOMComponent.prototype.updateMarkup)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>updateTextContent (nextContent)](#apidoc.element.react-dom.ReactDOMComponent.prototype.updateTextContent)

#### [module react-dom.ReactDOMComponentTree](#apidoc.module.react-dom.ReactDOMComponentTree)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponentTree.</span>getClosestInstanceFromNode (node)](#apidoc.element.react-dom.ReactDOMComponentTree.getClosestInstanceFromNode)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponentTree.</span>getInstanceFromNode (node)](#apidoc.element.react-dom.ReactDOMComponentTree.getInstanceFromNode)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponentTree.</span>getNodeFromInstance (inst)](#apidoc.element.react-dom.ReactDOMComponentTree.getNodeFromInstance)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponentTree.</span>precacheChildNodes (inst, node)](#apidoc.element.react-dom.ReactDOMComponentTree.precacheChildNodes)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponentTree.</span>precacheNode (inst, node)](#apidoc.element.react-dom.ReactDOMComponentTree.precacheNode)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMComponentTree.</span>uncacheNode (inst)](#apidoc.element.react-dom.ReactDOMComponentTree.uncacheNode)

#### [module react-dom.ReactDOMEmptyComponent](#apidoc.module.react-dom.ReactDOMEmptyComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ReactDOMEmptyComponent (instantiate)](#apidoc.element.react-dom.ReactDOMEmptyComponent.ReactDOMEmptyComponent)

#### [module react-dom.ReactDOMEmptyComponent.prototype](#apidoc.module.react-dom.ReactDOMEmptyComponent.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMEmptyComponent.prototype.</span>getHostNode ()](#apidoc.element.react-dom.ReactDOMEmptyComponent.prototype.getHostNode)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMEmptyComponent.prototype.</span>mountComponent (transaction, hostParent, hostContainerInfo, context)](#apidoc.element.react-dom.ReactDOMEmptyComponent.prototype.mountComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMEmptyComponent.prototype.</span>receiveComponent ()](#apidoc.element.react-dom.ReactDOMEmptyComponent.prototype.receiveComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMEmptyComponent.prototype.</span>unmountComponent ()](#apidoc.element.react-dom.ReactDOMEmptyComponent.prototype.unmountComponent)

#### [module react-dom.ReactDOMIDOperations](#apidoc.module.react-dom.ReactDOMIDOperations)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMIDOperations.</span>dangerouslyProcessChildrenUpdates (parentInst, updates)](#apidoc.element.react-dom.ReactDOMIDOperations.dangerouslyProcessChildrenUpdates)

#### [module react-dom.ReactDOMInput](#apidoc.module.react-dom.ReactDOMInput)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMInput.</span>getHostProps (inst, props)](#apidoc.element.react-dom.ReactDOMInput.getHostProps)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMInput.</span>mountWrapper (inst, props)](#apidoc.element.react-dom.ReactDOMInput.mountWrapper)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMInput.</span>postMountWrapper (inst)](#apidoc.element.react-dom.ReactDOMInput.postMountWrapper)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMInput.</span>updateWrapper (inst)](#apidoc.element.react-dom.ReactDOMInput.updateWrapper)

#### [module react-dom.ReactDOMInvalidARIAHook](#apidoc.module.react-dom.ReactDOMInvalidARIAHook)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMInvalidARIAHook.</span>onBeforeMountComponent (debugID, element)](#apidoc.element.react-dom.ReactDOMInvalidARIAHook.onBeforeMountComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMInvalidARIAHook.</span>onBeforeUpdateComponent (debugID, element)](#apidoc.element.react-dom.ReactDOMInvalidARIAHook.onBeforeUpdateComponent)

#### [module react-dom.ReactDOMNullInputValuePropHook](#apidoc.module.react-dom.ReactDOMNullInputValuePropHook)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMNullInputValuePropHook.</span>onBeforeMountComponent (debugID, element)](#apidoc.element.react-dom.ReactDOMNullInputValuePropHook.onBeforeMountComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMNullInputValuePropHook.</span>onBeforeUpdateComponent (debugID, element)](#apidoc.element.react-dom.ReactDOMNullInputValuePropHook.onBeforeUpdateComponent)

#### [module react-dom.ReactDOMOption](#apidoc.module.react-dom.ReactDOMOption)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMOption.</span>getHostProps (inst, props)](#apidoc.element.react-dom.ReactDOMOption.getHostProps)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMOption.</span>mountWrapper (inst, props, hostParent)](#apidoc.element.react-dom.ReactDOMOption.mountWrapper)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMOption.</span>postMountWrapper (inst)](#apidoc.element.react-dom.ReactDOMOption.postMountWrapper)

#### [module react-dom.ReactDOMSelect](#apidoc.module.react-dom.ReactDOMSelect)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMSelect.</span>getHostProps (inst, props)](#apidoc.element.react-dom.ReactDOMSelect.getHostProps)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMSelect.</span>getSelectValueContext (inst)](#apidoc.element.react-dom.ReactDOMSelect.getSelectValueContext)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMSelect.</span>mountWrapper (inst, props)](#apidoc.element.react-dom.ReactDOMSelect.mountWrapper)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMSelect.</span>postUpdateWrapper (inst)](#apidoc.element.react-dom.ReactDOMSelect.postUpdateWrapper)

#### [module react-dom.ReactDOMSelection](#apidoc.module.react-dom.ReactDOMSelection)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMSelection.</span>getOffsets (node)](#apidoc.element.react-dom.ReactDOMSelection.getOffsets)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMSelection.</span>setOffsets (node, offsets)](#apidoc.element.react-dom.ReactDOMSelection.setOffsets)

#### [module react-dom.ReactDOMServer](#apidoc.module.react-dom.ReactDOMServer)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMServer.</span>renderToStaticMarkup (element)](#apidoc.element.react-dom.ReactDOMServer.renderToStaticMarkup)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMServer.</span>renderToString (element)](#apidoc.element.react-dom.ReactDOMServer.renderToString)
1.  string <span class="apidocSignatureSpan">react-dom.ReactDOMServer.</span>version

#### [module react-dom.ReactDOMTextComponent](#apidoc.module.react-dom.ReactDOMTextComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ReactDOMTextComponent (text)](#apidoc.element.react-dom.ReactDOMTextComponent.ReactDOMTextComponent)

#### [module react-dom.ReactDOMTextComponent.prototype](#apidoc.module.react-dom.ReactDOMTextComponent.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMTextComponent.prototype.</span>getHostNode ()](#apidoc.element.react-dom.ReactDOMTextComponent.prototype.getHostNode)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMTextComponent.prototype.</span>mountComponent (transaction, hostParent, hostContainerInfo, context)](#apidoc.element.react-dom.ReactDOMTextComponent.prototype.mountComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMTextComponent.prototype.</span>receiveComponent (nextText, transaction)](#apidoc.element.react-dom.ReactDOMTextComponent.prototype.receiveComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMTextComponent.prototype.</span>unmountComponent ()](#apidoc.element.react-dom.ReactDOMTextComponent.prototype.unmountComponent)

#### [module react-dom.ReactDOMTextarea](#apidoc.module.react-dom.ReactDOMTextarea)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMTextarea.</span>getHostProps (inst, props)](#apidoc.element.react-dom.ReactDOMTextarea.getHostProps)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMTextarea.</span>mountWrapper (inst, props)](#apidoc.element.react-dom.ReactDOMTextarea.mountWrapper)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMTextarea.</span>postMountWrapper (inst)](#apidoc.element.react-dom.ReactDOMTextarea.postMountWrapper)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMTextarea.</span>updateWrapper (inst)](#apidoc.element.react-dom.ReactDOMTextarea.updateWrapper)

#### [module react-dom.ReactDOMTreeTraversal](#apidoc.module.react-dom.ReactDOMTreeTraversal)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMTreeTraversal.</span>getLowestCommonAncestor (instA, instB)](#apidoc.element.react-dom.ReactDOMTreeTraversal.getLowestCommonAncestor)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMTreeTraversal.</span>getParentInstance (inst)](#apidoc.element.react-dom.ReactDOMTreeTraversal.getParentInstance)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMTreeTraversal.</span>isAncestor (instA, instB)](#apidoc.element.react-dom.ReactDOMTreeTraversal.isAncestor)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMTreeTraversal.</span>traverseEnterLeave (from, to, fn, argFrom, argTo)](#apidoc.element.react-dom.ReactDOMTreeTraversal.traverseEnterLeave)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMTreeTraversal.</span>traverseTwoPhase (inst, fn, arg)](#apidoc.element.react-dom.ReactDOMTreeTraversal.traverseTwoPhase)

#### [module react-dom.ReactDOMUnknownPropertyHook](#apidoc.module.react-dom.ReactDOMUnknownPropertyHook)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMUnknownPropertyHook.</span>onBeforeMountComponent (debugID, element)](#apidoc.element.react-dom.ReactDOMUnknownPropertyHook.onBeforeMountComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDOMUnknownPropertyHook.</span>onBeforeUpdateComponent (debugID, element)](#apidoc.element.react-dom.ReactDOMUnknownPropertyHook.onBeforeUpdateComponent)

#### [module react-dom.ReactDebugTool](#apidoc.module.react-dom.ReactDebugTool)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>addDevtool (hook)](#apidoc.element.react-dom.ReactDebugTool.addDevtool)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>addHook (hook)](#apidoc.element.react-dom.ReactDebugTool.addHook)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>beginProfiling ()](#apidoc.element.react-dom.ReactDebugTool.beginProfiling)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>endProfiling ()](#apidoc.element.react-dom.ReactDebugTool.endProfiling)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>getFlushHistory ()](#apidoc.element.react-dom.ReactDebugTool.getFlushHistory)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>isProfiling ()](#apidoc.element.react-dom.ReactDebugTool.isProfiling)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onBeforeMountComponent (debugID, element, parentDebugID)](#apidoc.element.react-dom.ReactDebugTool.onBeforeMountComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onBeforeUnmountComponent (debugID)](#apidoc.element.react-dom.ReactDebugTool.onBeforeUnmountComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onBeforeUpdateComponent (debugID, element)](#apidoc.element.react-dom.ReactDebugTool.onBeforeUpdateComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onBeginFlush ()](#apidoc.element.react-dom.ReactDebugTool.onBeginFlush)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onBeginLifeCycleTimer (debugID, timerType)](#apidoc.element.react-dom.ReactDebugTool.onBeginLifeCycleTimer)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onBeginProcessingChildContext ()](#apidoc.element.react-dom.ReactDebugTool.onBeginProcessingChildContext)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onEndFlush ()](#apidoc.element.react-dom.ReactDebugTool.onEndFlush)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onEndLifeCycleTimer (debugID, timerType)](#apidoc.element.react-dom.ReactDebugTool.onEndLifeCycleTimer)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onEndProcessingChildContext ()](#apidoc.element.react-dom.ReactDebugTool.onEndProcessingChildContext)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onHostOperation (operation)](#apidoc.element.react-dom.ReactDebugTool.onHostOperation)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onMountComponent (debugID)](#apidoc.element.react-dom.ReactDebugTool.onMountComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onSetChildren (debugID, childDebugIDs)](#apidoc.element.react-dom.ReactDebugTool.onSetChildren)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onSetState ()](#apidoc.element.react-dom.ReactDebugTool.onSetState)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onTestEvent ()](#apidoc.element.react-dom.ReactDebugTool.onTestEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onUnmountComponent (debugID)](#apidoc.element.react-dom.ReactDebugTool.onUnmountComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onUpdateComponent (debugID)](#apidoc.element.react-dom.ReactDebugTool.onUpdateComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>removeDevtool (hook)](#apidoc.element.react-dom.ReactDebugTool.removeDevtool)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>removeHook (hook)](#apidoc.element.react-dom.ReactDebugTool.removeHook)

#### [module react-dom.ReactDefaultBatchingStrategy](#apidoc.module.react-dom.ReactDefaultBatchingStrategy)
1.  boolean <span class="apidocSignatureSpan">react-dom.ReactDefaultBatchingStrategy.</span>isBatchingUpdates
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDefaultBatchingStrategy.</span>batchedUpdates (callback, a, b, c, d, e)](#apidoc.element.react-dom.ReactDefaultBatchingStrategy.batchedUpdates)

#### [module react-dom.ReactDefaultInjection](#apidoc.module.react-dom.ReactDefaultInjection)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactDefaultInjection.</span>inject ()](#apidoc.element.react-dom.ReactDefaultInjection.inject)

#### [module react-dom.ReactEmptyComponent](#apidoc.module.react-dom.ReactEmptyComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactEmptyComponent.</span>create (instantiate)](#apidoc.element.react-dom.ReactEmptyComponent.create)
1.  object <span class="apidocSignatureSpan">react-dom.ReactEmptyComponent.</span>injection

#### [module react-dom.ReactErrorUtils](#apidoc.module.react-dom.ReactErrorUtils)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactErrorUtils.</span>invokeGuardedCallback (name, func, a)](#apidoc.element.react-dom.ReactErrorUtils.invokeGuardedCallback)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactErrorUtils.</span>invokeGuardedCallbackWithCatch (name, func, a)](#apidoc.element.react-dom.ReactErrorUtils.invokeGuardedCallbackWithCatch)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactErrorUtils.</span>rethrowCaughtError ()](#apidoc.element.react-dom.ReactErrorUtils.rethrowCaughtError)

#### [module react-dom.ReactEventEmitterMixin](#apidoc.module.react-dom.ReactEventEmitterMixin)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactEventEmitterMixin.</span>handleTopLevel (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.ReactEventEmitterMixin.handleTopLevel)

#### [module react-dom.ReactEventListener](#apidoc.module.react-dom.ReactEventListener)
1.  boolean <span class="apidocSignatureSpan">react-dom.ReactEventListener.</span>_enabled
1.  [function <span class="apidocSignatureSpan">react-dom.ReactEventListener.</span>_handleTopLevel (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.ReactEventListener._handleTopLevel)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactEventListener.</span>dispatchEvent (topLevelType, nativeEvent)](#apidoc.element.react-dom.ReactEventListener.dispatchEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactEventListener.</span>isEnabled ()](#apidoc.element.react-dom.ReactEventListener.isEnabled)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactEventListener.</span>monitorScrollValue (refresh)](#apidoc.element.react-dom.ReactEventListener.monitorScrollValue)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactEventListener.</span>setEnabled (enabled)](#apidoc.element.react-dom.ReactEventListener.setEnabled)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactEventListener.</span>setHandleTopLevel (handleTopLevel)](#apidoc.element.react-dom.ReactEventListener.setHandleTopLevel)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactEventListener.</span>trapBubbledEvent (topLevelType, handlerBaseName, element)](#apidoc.element.react-dom.ReactEventListener.trapBubbledEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactEventListener.</span>trapCapturedEvent (topLevelType, handlerBaseName, element)](#apidoc.element.react-dom.ReactEventListener.trapCapturedEvent)
1.  object <span class="apidocSignatureSpan">react-dom.ReactEventListener.</span>WINDOW_HANDLE

#### [module react-dom.ReactFiber](#apidoc.module.react-dom.ReactFiber)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactFiber.</span>cloneFiber (fiber, priorityLevel)](#apidoc.element.react-dom.ReactFiber.cloneFiber)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactFiber.</span>createFiberFromCoroutine (coroutine, priorityLevel)](#apidoc.element.react-dom.ReactFiber.createFiberFromCoroutine)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactFiber.</span>createFiberFromElement (element, priorityLevel)](#apidoc.element.react-dom.ReactFiber.createFiberFromElement)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactFiber.</span>createFiberFromElementType (type, key)](#apidoc.element.react-dom.ReactFiber.createFiberFromElementType)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactFiber.</span>createFiberFromYield (yieldNode, priorityLevel)](#apidoc.element.react-dom.ReactFiber.createFiberFromYield)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactFiber.</span>createHostContainerFiber ()](#apidoc.element.react-dom.ReactFiber.createHostContainerFiber)

#### [module react-dom.ReactFiberRoot](#apidoc.module.react-dom.ReactFiberRoot)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactFiberRoot.</span>createFiberRoot (containerInfo)](#apidoc.element.react-dom.ReactFiberRoot.createFiberRoot)

#### [module react-dom.ReactFiberUpdateQueue](#apidoc.module.react-dom.ReactFiberUpdateQueue)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactFiberUpdateQueue.</span>addCallbackToQueue (queue, callback)](#apidoc.element.react-dom.ReactFiberUpdateQueue.addCallbackToQueue)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactFiberUpdateQueue.</span>addToQueue (queue, partialState)](#apidoc.element.react-dom.ReactFiberUpdateQueue.addToQueue)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactFiberUpdateQueue.</span>callCallbacks (queue, context)](#apidoc.element.react-dom.ReactFiberUpdateQueue.callCallbacks)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactFiberUpdateQueue.</span>createUpdateQueue (partialState)](#apidoc.element.react-dom.ReactFiberUpdateQueue.createUpdateQueue)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactFiberUpdateQueue.</span>mergeUpdateQueue (queue, prevState, props)](#apidoc.element.react-dom.ReactFiberUpdateQueue.mergeUpdateQueue)

#### [module react-dom.ReactHostComponent](#apidoc.module.react-dom.ReactHostComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactHostComponent.</span>createInstanceForText (text)](#apidoc.element.react-dom.ReactHostComponent.createInstanceForText)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactHostComponent.</span>createInternalComponent (element)](#apidoc.element.react-dom.ReactHostComponent.createInternalComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactHostComponent.</span>isTextComponent (component)](#apidoc.element.react-dom.ReactHostComponent.isTextComponent)
1.  object <span class="apidocSignatureSpan">react-dom.ReactHostComponent.</span>injection

#### [module react-dom.ReactHostOperationHistoryHook](#apidoc.module.react-dom.ReactHostOperationHistoryHook)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactHostOperationHistoryHook.</span>clearHistory ()](#apidoc.element.react-dom.ReactHostOperationHistoryHook.clearHistory)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactHostOperationHistoryHook.</span>getHistory ()](#apidoc.element.react-dom.ReactHostOperationHistoryHook.getHistory)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactHostOperationHistoryHook.</span>onHostOperation (operation)](#apidoc.element.react-dom.ReactHostOperationHistoryHook.onHostOperation)

#### [module react-dom.ReactInputSelection](#apidoc.module.react-dom.ReactInputSelection)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactInputSelection.</span>getSelection (input)](#apidoc.element.react-dom.ReactInputSelection.getSelection)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactInputSelection.</span>getSelectionInformation ()](#apidoc.element.react-dom.ReactInputSelection.getSelectionInformation)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactInputSelection.</span>hasSelectionCapabilities (elem)](#apidoc.element.react-dom.ReactInputSelection.hasSelectionCapabilities)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactInputSelection.</span>restoreSelection (priorSelectionInformation)](#apidoc.element.react-dom.ReactInputSelection.restoreSelection)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactInputSelection.</span>setSelection (input, offsets)](#apidoc.element.react-dom.ReactInputSelection.setSelection)

#### [module react-dom.ReactInstanceMap](#apidoc.module.react-dom.ReactInstanceMap)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactInstanceMap.</span>get (key)](#apidoc.element.react-dom.ReactInstanceMap.get)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactInstanceMap.</span>has (key)](#apidoc.element.react-dom.ReactInstanceMap.has)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactInstanceMap.</span>remove (key)](#apidoc.element.react-dom.ReactInstanceMap.remove)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactInstanceMap.</span>set (key, value)](#apidoc.element.react-dom.ReactInstanceMap.set)

#### [module react-dom.ReactInvalidSetStateWarningHook](#apidoc.module.react-dom.ReactInvalidSetStateWarningHook)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactInvalidSetStateWarningHook.</span>onBeginProcessingChildContext ()](#apidoc.element.react-dom.ReactInvalidSetStateWarningHook.onBeginProcessingChildContext)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactInvalidSetStateWarningHook.</span>onEndProcessingChildContext ()](#apidoc.element.react-dom.ReactInvalidSetStateWarningHook.onEndProcessingChildContext)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactInvalidSetStateWarningHook.</span>onSetState ()](#apidoc.element.react-dom.ReactInvalidSetStateWarningHook.onSetState)

#### [module react-dom.ReactMarkupChecksum](#apidoc.module.react-dom.ReactMarkupChecksum)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactMarkupChecksum.</span>addChecksumToMarkup (markup)](#apidoc.element.react-dom.ReactMarkupChecksum.addChecksumToMarkup)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactMarkupChecksum.</span>canReuseMarkup (markup, element)](#apidoc.element.react-dom.ReactMarkupChecksum.canReuseMarkup)
1.  string <span class="apidocSignatureSpan">react-dom.ReactMarkupChecksum.</span>CHECKSUM_ATTR_NAME

#### [module react-dom.ReactMount](#apidoc.module.react-dom.ReactMount)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactMount.</span>TopLevelWrapper ()](#apidoc.element.react-dom.ReactMount.TopLevelWrapper)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactMount.</span>_mountImageIntoNode (markup, container, instance, shouldReuseMarkup, transaction)](#apidoc.element.react-dom.ReactMount._mountImageIntoNode)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactMount.</span>_renderNewRootComponent (nextElement, container, shouldReuseMarkup, context)](#apidoc.element.react-dom.ReactMount._renderNewRootComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactMount.</span>_renderSubtreeIntoContainer (parentComponent, nextElement, container, callback)](#apidoc.element.react-dom.ReactMount._renderSubtreeIntoContainer)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactMount.</span>_updateRootComponent (prevComponent, nextElement, nextContext, container, callback)](#apidoc.element.react-dom.ReactMount._updateRootComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactMount.</span>render (nextElement, container, callback)](#apidoc.element.react-dom.ReactMount.render)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactMount.</span>renderSubtreeIntoContainer (parentComponent, nextElement, container, callback)](#apidoc.element.react-dom.ReactMount.renderSubtreeIntoContainer)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactMount.</span>scrollMonitor (container, renderCallback)](#apidoc.element.react-dom.ReactMount.scrollMonitor)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactMount.</span>unmountComponentAtNode (container)](#apidoc.element.react-dom.ReactMount.unmountComponentAtNode)
1.  object <span class="apidocSignatureSpan">react-dom.ReactMount.</span>_instancesByReactRootID

#### [module react-dom.ReactNodeTypes](#apidoc.module.react-dom.ReactNodeTypes)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactNodeTypes.</span>getType (node)](#apidoc.element.react-dom.ReactNodeTypes.getType)
1.  number <span class="apidocSignatureSpan">react-dom.ReactNodeTypes.</span>COMPOSITE
1.  number <span class="apidocSignatureSpan">react-dom.ReactNodeTypes.</span>EMPTY
1.  number <span class="apidocSignatureSpan">react-dom.ReactNodeTypes.</span>HOST

#### [module react-dom.ReactOwner](#apidoc.module.react-dom.ReactOwner)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactOwner.</span>addComponentAsRefTo (component, ref, owner)](#apidoc.element.react-dom.ReactOwner.addComponentAsRefTo)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactOwner.</span>removeComponentAsRefFrom (component, ref, owner)](#apidoc.element.react-dom.ReactOwner.removeComponentAsRefFrom)

#### [module react-dom.ReactPerf](#apidoc.module.react-dom.ReactPerf)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>getExclusive ()](#apidoc.element.react-dom.ReactPerf.getExclusive)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>getInclusive ()](#apidoc.element.react-dom.ReactPerf.getInclusive)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>getLastMeasurements ()](#apidoc.element.react-dom.ReactPerf.getLastMeasurements)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>getMeasurementsSummaryMap (measurements)](#apidoc.element.react-dom.ReactPerf.getMeasurementsSummaryMap)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>getOperations ()](#apidoc.element.react-dom.ReactPerf.getOperations)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>getWasted ()](#apidoc.element.react-dom.ReactPerf.getWasted)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>isRunning ()](#apidoc.element.react-dom.ReactPerf.isRunning)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>printDOM (measurements)](#apidoc.element.react-dom.ReactPerf.printDOM)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>printExclusive (flushHistory)](#apidoc.element.react-dom.ReactPerf.printExclusive)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>printInclusive (flushHistory)](#apidoc.element.react-dom.ReactPerf.printInclusive)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>printOperations (flushHistory)](#apidoc.element.react-dom.ReactPerf.printOperations)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>printWasted (flushHistory)](#apidoc.element.react-dom.ReactPerf.printWasted)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>start ()](#apidoc.element.react-dom.ReactPerf.start)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>stop ()](#apidoc.element.react-dom.ReactPerf.stop)

#### [module react-dom.ReactReconcileTransaction](#apidoc.module.react-dom.ReactReconcileTransaction)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ReactReconcileTransaction (useCreateElement)](#apidoc.element.react-dom.ReactReconcileTransaction.ReactReconcileTransaction)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.</span>getPooled (copyFieldsFrom)](#apidoc.element.react-dom.ReactReconcileTransaction.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.</span>release (instance)](#apidoc.element.react-dom.ReactReconcileTransaction.release)
1.  number <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.</span>instancePool

#### [module react-dom.ReactReconcileTransaction.prototype](#apidoc.module.react-dom.ReactReconcileTransaction.prototype)
1.  boolean <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>_isInTransaction
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>checkpoint ()](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.checkpoint)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>closeAll (startIndex)](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.closeAll)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>destructor ()](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.destructor)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>getReactMountReady ()](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.getReactMountReady)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>getTransactionWrappers ()](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.getTransactionWrappers)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>getUpdateQueue ()](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.getUpdateQueue)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>initializeAll (startIndex)](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.initializeAll)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>isInTransaction ()](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.isInTransaction)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>perform (method, scope, a, b, c, d, e, f)](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.perform)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>reinitializeTransaction ()](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.reinitializeTransaction)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>rollback (checkpoint)](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.rollback)

#### [module react-dom.ReactReconciler](#apidoc.module.react-dom.ReactReconciler)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReconciler.</span>getHostNode (internalInstance)](#apidoc.element.react-dom.ReactReconciler.getHostNode)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReconciler.</span>mountComponent (internalInstance, transaction, hostParent, hostContainerInfo, context, parentDebugID // 0 in production and for roots )](#apidoc.element.react-dom.ReactReconciler.mountComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReconciler.</span>performUpdateIfNecessary (internalInstance, transaction, updateBatchNumber)](#apidoc.element.react-dom.ReactReconciler.performUpdateIfNecessary)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReconciler.</span>receiveComponent (internalInstance, nextElement, transaction, context)](#apidoc.element.react-dom.ReactReconciler.receiveComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReconciler.</span>unmountComponent (internalInstance, safely)](#apidoc.element.react-dom.ReactReconciler.unmountComponent)

#### [module react-dom.ReactRef](#apidoc.module.react-dom.ReactRef)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactRef.</span>attachRefs (instance, element)](#apidoc.element.react-dom.ReactRef.attachRefs)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactRef.</span>detachRefs (instance, element)](#apidoc.element.react-dom.ReactRef.detachRefs)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactRef.</span>shouldUpdateRefs (prevElement, nextElement)](#apidoc.element.react-dom.ReactRef.shouldUpdateRefs)

#### [module react-dom.ReactReifiedYield](#apidoc.module.react-dom.ReactReifiedYield)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReifiedYield.</span>createReifiedYield (yieldNode)](#apidoc.element.react-dom.ReactReifiedYield.createReifiedYield)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactReifiedYield.</span>createUpdatedReifiedYield (previousYield, yieldNode)](#apidoc.element.react-dom.ReactReifiedYield.createUpdatedReifiedYield)

#### [module react-dom.ReactServerBatchingStrategy](#apidoc.module.react-dom.ReactServerBatchingStrategy)
1.  boolean <span class="apidocSignatureSpan">react-dom.ReactServerBatchingStrategy.</span>isBatchingUpdates
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerBatchingStrategy.</span>batchedUpdates (callback)](#apidoc.element.react-dom.ReactServerBatchingStrategy.batchedUpdates)

#### [module react-dom.ReactServerRendering](#apidoc.module.react-dom.ReactServerRendering)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerRendering.</span>renderToStaticMarkup (element)](#apidoc.element.react-dom.ReactServerRendering.renderToStaticMarkup)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerRendering.</span>renderToString (element)](#apidoc.element.react-dom.ReactServerRendering.renderToString)

#### [module react-dom.ReactServerRenderingTransaction](#apidoc.module.react-dom.ReactServerRenderingTransaction)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ReactServerRenderingTransaction (renderToStaticMarkup)](#apidoc.element.react-dom.ReactServerRenderingTransaction.ReactServerRenderingTransaction)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.</span>getPooled (copyFieldsFrom)](#apidoc.element.react-dom.ReactServerRenderingTransaction.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.</span>release (instance)](#apidoc.element.react-dom.ReactServerRenderingTransaction.release)
1.  number <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.</span>instancePool

#### [module react-dom.ReactServerRenderingTransaction.prototype](#apidoc.module.react-dom.ReactServerRenderingTransaction.prototype)
1.  boolean <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>_isInTransaction
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>checkpoint ()](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.checkpoint)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>closeAll (startIndex)](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.closeAll)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>destructor ()](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.destructor)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>getReactMountReady ()](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.getReactMountReady)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>getTransactionWrappers ()](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.getTransactionWrappers)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>getUpdateQueue ()](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.getUpdateQueue)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>initializeAll (startIndex)](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.initializeAll)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>isInTransaction ()](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.isInTransaction)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>perform (method, scope, a, b, c, d, e, f)](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.perform)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>reinitializeTransaction ()](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.reinitializeTransaction)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>rollback ()](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.rollback)

#### [module react-dom.ReactServerUpdateQueue](#apidoc.module.react-dom.ReactServerUpdateQueue)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ReactServerUpdateQueue (transaction)](#apidoc.element.react-dom.ReactServerUpdateQueue.ReactServerUpdateQueue)

#### [module react-dom.ReactServerUpdateQueue.prototype](#apidoc.module.react-dom.ReactServerUpdateQueue.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerUpdateQueue.prototype.</span>enqueueCallback (publicInstance, callback, callerName)](#apidoc.element.react-dom.ReactServerUpdateQueue.prototype.enqueueCallback)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerUpdateQueue.prototype.</span>enqueueForceUpdate (publicInstance)](#apidoc.element.react-dom.ReactServerUpdateQueue.prototype.enqueueForceUpdate)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerUpdateQueue.prototype.</span>enqueueReplaceState (publicInstance, completeState)](#apidoc.element.react-dom.ReactServerUpdateQueue.prototype.enqueueReplaceState)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerUpdateQueue.prototype.</span>enqueueSetState (publicInstance, partialState)](#apidoc.element.react-dom.ReactServerUpdateQueue.prototype.enqueueSetState)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactServerUpdateQueue.prototype.</span>isMounted (publicInstance)](#apidoc.element.react-dom.ReactServerUpdateQueue.prototype.isMounted)

#### [module react-dom.ReactShallowRenderer](#apidoc.module.react-dom.ReactShallowRenderer)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ReactShallowRenderer ()](#apidoc.element.react-dom.ReactShallowRenderer.ReactShallowRenderer)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactShallowRenderer.</span>createRenderer ()](#apidoc.element.react-dom.ReactShallowRenderer.createRenderer)

#### [module react-dom.ReactShallowRenderer.prototype](#apidoc.module.react-dom.ReactShallowRenderer.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactShallowRenderer.prototype.</span>_render (element, transaction, context)](#apidoc.element.react-dom.ReactShallowRenderer.prototype._render)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactShallowRenderer.prototype.</span>getMountedInstance ()](#apidoc.element.react-dom.ReactShallowRenderer.prototype.getMountedInstance)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactShallowRenderer.prototype.</span>getRenderOutput ()](#apidoc.element.react-dom.ReactShallowRenderer.prototype.getRenderOutput)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactShallowRenderer.prototype.</span>render (element, context)](#apidoc.element.react-dom.ReactShallowRenderer.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactShallowRenderer.prototype.</span>unmount ()](#apidoc.element.react-dom.ReactShallowRenderer.prototype.unmount)

#### [module react-dom.ReactSimpleEmptyComponent](#apidoc.module.react-dom.ReactSimpleEmptyComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ReactSimpleEmptyComponent (placeholderElement, instantiate)](#apidoc.element.react-dom.ReactSimpleEmptyComponent.ReactSimpleEmptyComponent)

#### [module react-dom.ReactSimpleEmptyComponent.prototype](#apidoc.module.react-dom.ReactSimpleEmptyComponent.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactSimpleEmptyComponent.prototype.</span>getHostNode ()](#apidoc.element.react-dom.ReactSimpleEmptyComponent.prototype.getHostNode)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactSimpleEmptyComponent.prototype.</span>mountComponent (transaction, hostParent, hostContainerInfo, context, parentDebugID // 0 in production and for roots )](#apidoc.element.react-dom.ReactSimpleEmptyComponent.prototype.mountComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactSimpleEmptyComponent.prototype.</span>receiveComponent ()](#apidoc.element.react-dom.ReactSimpleEmptyComponent.prototype.receiveComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactSimpleEmptyComponent.prototype.</span>unmountComponent ()](#apidoc.element.react-dom.ReactSimpleEmptyComponent.prototype.unmountComponent)

#### [module react-dom.ReactTestReconcileTransaction](#apidoc.module.react-dom.ReactTestReconcileTransaction)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ReactTestReconcileTransaction (testOptions)](#apidoc.element.react-dom.ReactTestReconcileTransaction.ReactTestReconcileTransaction)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.</span>getPooled (copyFieldsFrom)](#apidoc.element.react-dom.ReactTestReconcileTransaction.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.</span>release (instance)](#apidoc.element.react-dom.ReactTestReconcileTransaction.release)
1.  number <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.</span>instancePool

#### [module react-dom.ReactTestReconcileTransaction.prototype](#apidoc.module.react-dom.ReactTestReconcileTransaction.prototype)
1.  boolean <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>_isInTransaction
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>checkpoint ()](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.checkpoint)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>closeAll (startIndex)](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.closeAll)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>destructor ()](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.destructor)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>getReactMountReady ()](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.getReactMountReady)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>getTestOptions ()](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.getTestOptions)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>getTransactionWrappers ()](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.getTransactionWrappers)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>getUpdateQueue ()](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.getUpdateQueue)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>initializeAll (startIndex)](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.initializeAll)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>isInTransaction ()](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.isInTransaction)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>perform (method, scope, a, b, c, d, e, f)](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.perform)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>reinitializeTransaction ()](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.reinitializeTransaction)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>rollback (checkpoint)](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.rollback)

#### [module react-dom.ReactTestUtils](#apidoc.module.react-dom.ReactTestUtils)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>createRenderer ()](#apidoc.element.react-dom.ReactTestUtils.createRenderer)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>findAllInRenderedTree (inst, test)](#apidoc.element.react-dom.ReactTestUtils.findAllInRenderedTree)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>findRenderedComponentWithType (root, componentType)](#apidoc.element.react-dom.ReactTestUtils.findRenderedComponentWithType)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>findRenderedDOMComponentWithClass (root, className)](#apidoc.element.react-dom.ReactTestUtils.findRenderedDOMComponentWithClass)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>findRenderedDOMComponentWithTag (root, tagName)](#apidoc.element.react-dom.ReactTestUtils.findRenderedDOMComponentWithTag)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>getRenderedChildOfCompositeComponent (inst)](#apidoc.element.react-dom.ReactTestUtils.getRenderedChildOfCompositeComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>isCompositeComponent (inst)](#apidoc.element.react-dom.ReactTestUtils.isCompositeComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>isCompositeComponentElement (inst)](#apidoc.element.react-dom.ReactTestUtils.isCompositeComponentElement)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>isCompositeComponentElementWithType (inst, type)](#apidoc.element.react-dom.ReactTestUtils.isCompositeComponentElementWithType)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>isCompositeComponentWithType (inst, type)](#apidoc.element.react-dom.ReactTestUtils.isCompositeComponentWithType)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>isDOMComponent (inst)](#apidoc.element.react-dom.ReactTestUtils.isDOMComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>isDOMComponentElement (inst)](#apidoc.element.react-dom.ReactTestUtils.isDOMComponentElement)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>isElement (element)](#apidoc.element.react-dom.ReactTestUtils.isElement)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>isElementOfType (inst, convenienceConstructor)](#apidoc.element.react-dom.ReactTestUtils.isElementOfType)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>mockComponent (module, mockTagName)](#apidoc.element.react-dom.ReactTestUtils.mockComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>nativeTouchData (x, y)](#apidoc.element.react-dom.ReactTestUtils.nativeTouchData)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>renderIntoDocument (element)](#apidoc.element.react-dom.ReactTestUtils.renderIntoDocument)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>scryRenderedComponentsWithType (root, componentType)](#apidoc.element.react-dom.ReactTestUtils.scryRenderedComponentsWithType)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>scryRenderedDOMComponentsWithClass (root, classNames)](#apidoc.element.react-dom.ReactTestUtils.scryRenderedDOMComponentsWithClass)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>scryRenderedDOMComponentsWithTag (root, tagName)](#apidoc.element.react-dom.ReactTestUtils.scryRenderedDOMComponentsWithTag)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>simulateNativeEventOnDOMComponent (topLevelType, comp, fakeNativeEvent)](#apidoc.element.react-dom.ReactTestUtils.simulateNativeEventOnDOMComponent)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>simulateNativeEventOnNode (topLevelType, node, fakeNativeEvent)](#apidoc.element.react-dom.ReactTestUtils.simulateNativeEventOnNode)
1.  object <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>Simulate
1.  object <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>SimulateNative

#### [module react-dom.ReactUpdateQueue](#apidoc.module.react-dom.ReactUpdateQueue)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactUpdateQueue.</span>enqueueCallback (publicInstance, callback, callerName)](#apidoc.element.react-dom.ReactUpdateQueue.enqueueCallback)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactUpdateQueue.</span>enqueueCallbackInternal (internalInstance, callback)](#apidoc.element.react-dom.ReactUpdateQueue.enqueueCallbackInternal)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactUpdateQueue.</span>enqueueElementInternal (internalInstance, nextElement, nextContext)](#apidoc.element.react-dom.ReactUpdateQueue.enqueueElementInternal)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactUpdateQueue.</span>enqueueForceUpdate (publicInstance)](#apidoc.element.react-dom.ReactUpdateQueue.enqueueForceUpdate)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactUpdateQueue.</span>enqueueReplaceState (publicInstance, completeState, callback)](#apidoc.element.react-dom.ReactUpdateQueue.enqueueReplaceState)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactUpdateQueue.</span>enqueueSetState (publicInstance, partialState)](#apidoc.element.react-dom.ReactUpdateQueue.enqueueSetState)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactUpdateQueue.</span>isMounted (publicInstance)](#apidoc.element.react-dom.ReactUpdateQueue.isMounted)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactUpdateQueue.</span>validateCallback (callback, callerName)](#apidoc.element.react-dom.ReactUpdateQueue.validateCallback)

#### [module react-dom.ReactUpdates](#apidoc.module.react-dom.ReactUpdates)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactUpdates.</span>ReactReconcileTransaction (useCreateElement)](#apidoc.element.react-dom.ReactUpdates.ReactReconcileTransaction)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactUpdates.</span>asap (callback, context)](#apidoc.element.react-dom.ReactUpdates.asap)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactUpdates.</span>batchedUpdates (callback, a, b, c, d, e)](#apidoc.element.react-dom.ReactUpdates.batchedUpdates)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactUpdates.</span>enqueueUpdate (component)](#apidoc.element.react-dom.ReactUpdates.enqueueUpdate)
1.  [function <span class="apidocSignatureSpan">react-dom.ReactUpdates.</span>flushBatchedUpdates ()](#apidoc.element.react-dom.ReactUpdates.flushBatchedUpdates)
1.  object <span class="apidocSignatureSpan">react-dom.ReactUpdates.</span>injection

#### [module react-dom.ResponderEventPlugin](#apidoc.module.react-dom.ResponderEventPlugin)
1.  [function <span class="apidocSignatureSpan">react-dom.ResponderEventPlugin.</span>_getResponderID ()](#apidoc.element.react-dom.ResponderEventPlugin._getResponderID)
1.  [function <span class="apidocSignatureSpan">react-dom.ResponderEventPlugin.</span>extractEvents (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.ResponderEventPlugin.extractEvents)
1.  object <span class="apidocSignatureSpan">react-dom.ResponderEventPlugin.</span>GlobalInteractionHandler
1.  object <span class="apidocSignatureSpan">react-dom.ResponderEventPlugin.</span>GlobalResponderHandler
1.  object <span class="apidocSignatureSpan">react-dom.ResponderEventPlugin.</span>eventTypes
1.  object <span class="apidocSignatureSpan">react-dom.ResponderEventPlugin.</span>injection

#### [module react-dom.ResponderSyntheticEvent](#apidoc.module.react-dom.ResponderSyntheticEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>ResponderSyntheticEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.ResponderSyntheticEvent.ResponderSyntheticEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.ResponderSyntheticEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.ResponderSyntheticEvent.augmentClass)
1.  [function <span class="apidocSignatureSpan">react-dom.ResponderSyntheticEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.ResponderSyntheticEvent.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.ResponderSyntheticEvent.</span>release (instance)](#apidoc.element.react-dom.ResponderSyntheticEvent.release)
1.  number <span class="apidocSignatureSpan">react-dom.ResponderSyntheticEvent.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.ResponderSyntheticEvent.</span>Interface
1.  object <span class="apidocSignatureSpan">react-dom.ResponderSyntheticEvent.</span>instancePool

#### [module react-dom.ResponderSyntheticEvent.prototype](#apidoc.module.react-dom.ResponderSyntheticEvent.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.ResponderSyntheticEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.ResponderSyntheticEvent.prototype.constructor)

#### [module react-dom.ResponderTouchHistoryStore](#apidoc.module.react-dom.ResponderTouchHistoryStore)
1.  [function <span class="apidocSignatureSpan">react-dom.ResponderTouchHistoryStore.</span>recordTouchTrack (topLevelType, nativeEvent)](#apidoc.element.react-dom.ResponderTouchHistoryStore.recordTouchTrack)
1.  object <span class="apidocSignatureSpan">react-dom.ResponderTouchHistoryStore.</span>touchHistory

#### [module react-dom.SelectEventPlugin](#apidoc.module.react-dom.SelectEventPlugin)
1.  [function <span class="apidocSignatureSpan">react-dom.SelectEventPlugin.</span>didPutListener (inst, registrationName, listener)](#apidoc.element.react-dom.SelectEventPlugin.didPutListener)
1.  [function <span class="apidocSignatureSpan">react-dom.SelectEventPlugin.</span>extractEvents (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SelectEventPlugin.extractEvents)
1.  object <span class="apidocSignatureSpan">react-dom.SelectEventPlugin.</span>eventTypes

#### [module react-dom.SimpleEventPlugin](#apidoc.module.react-dom.SimpleEventPlugin)
1.  [function <span class="apidocSignatureSpan">react-dom.SimpleEventPlugin.</span>didPutListener (inst, registrationName, listener)](#apidoc.element.react-dom.SimpleEventPlugin.didPutListener)
1.  [function <span class="apidocSignatureSpan">react-dom.SimpleEventPlugin.</span>extractEvents (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SimpleEventPlugin.extractEvents)
1.  [function <span class="apidocSignatureSpan">react-dom.SimpleEventPlugin.</span>willDeleteListener (inst, registrationName)](#apidoc.element.react-dom.SimpleEventPlugin.willDeleteListener)
1.  object <span class="apidocSignatureSpan">react-dom.SimpleEventPlugin.</span>eventTypes

#### [module react-dom.SyntheticAnimationEvent](#apidoc.module.react-dom.SyntheticAnimationEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticAnimationEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticAnimationEvent.SyntheticAnimationEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticAnimationEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticAnimationEvent.augmentClass)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticAnimationEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticAnimationEvent.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticAnimationEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticAnimationEvent.release)
1.  number <span class="apidocSignatureSpan">react-dom.SyntheticAnimationEvent.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticAnimationEvent.</span>Interface
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticAnimationEvent.</span>instancePool

#### [module react-dom.SyntheticAnimationEvent.prototype](#apidoc.module.react-dom.SyntheticAnimationEvent.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticAnimationEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticAnimationEvent.prototype.constructor)

#### [module react-dom.SyntheticClipboardEvent](#apidoc.module.react-dom.SyntheticClipboardEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticClipboardEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticClipboardEvent.SyntheticClipboardEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticClipboardEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticClipboardEvent.augmentClass)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticClipboardEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticClipboardEvent.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticClipboardEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticClipboardEvent.release)
1.  number <span class="apidocSignatureSpan">react-dom.SyntheticClipboardEvent.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticClipboardEvent.</span>Interface
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticClipboardEvent.</span>instancePool

#### [module react-dom.SyntheticClipboardEvent.prototype](#apidoc.module.react-dom.SyntheticClipboardEvent.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticClipboardEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticClipboardEvent.prototype.constructor)

#### [module react-dom.SyntheticCompositionEvent](#apidoc.module.react-dom.SyntheticCompositionEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticCompositionEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticCompositionEvent.SyntheticCompositionEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticCompositionEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticCompositionEvent.augmentClass)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticCompositionEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticCompositionEvent.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticCompositionEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticCompositionEvent.release)
1.  number <span class="apidocSignatureSpan">react-dom.SyntheticCompositionEvent.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticCompositionEvent.</span>Interface
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticCompositionEvent.</span>instancePool

#### [module react-dom.SyntheticCompositionEvent.prototype](#apidoc.module.react-dom.SyntheticCompositionEvent.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticCompositionEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticCompositionEvent.prototype.constructor)

#### [module react-dom.SyntheticDragEvent](#apidoc.module.react-dom.SyntheticDragEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticDragEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticDragEvent.SyntheticDragEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticDragEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticDragEvent.augmentClass)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticDragEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticDragEvent.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticDragEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticDragEvent.release)
1.  number <span class="apidocSignatureSpan">react-dom.SyntheticDragEvent.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticDragEvent.</span>Interface
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticDragEvent.</span>instancePool

#### [module react-dom.SyntheticDragEvent.prototype](#apidoc.module.react-dom.SyntheticDragEvent.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticDragEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticDragEvent.prototype.constructor)

#### [module react-dom.SyntheticEvent](#apidoc.module.react-dom.SyntheticEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticEvent {{signature}}](#apidoc.element.react-dom.SyntheticEvent.SyntheticEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticEvent.augmentClass)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticEvent.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticEvent.release)
1.  number <span class="apidocSignatureSpan">react-dom.SyntheticEvent.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticEvent.</span>Interface
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticEvent.</span>instancePool

#### [module react-dom.SyntheticEvent.prototype](#apidoc.module.react-dom.SyntheticEvent.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticEvent.prototype.</span>destructor ()](#apidoc.element.react-dom.SyntheticEvent.prototype.destructor)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticEvent.prototype.</span>isPersistent ()](#apidoc.element.react-dom.SyntheticEvent.prototype.isPersistent)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticEvent.prototype.</span>persist ()](#apidoc.element.react-dom.SyntheticEvent.prototype.persist)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticEvent.prototype.</span>preventDefault ()](#apidoc.element.react-dom.SyntheticEvent.prototype.preventDefault)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticEvent.prototype.</span>stopPropagation ()](#apidoc.element.react-dom.SyntheticEvent.prototype.stopPropagation)

#### [module react-dom.SyntheticFocusEvent](#apidoc.module.react-dom.SyntheticFocusEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticFocusEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticFocusEvent.SyntheticFocusEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticFocusEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticFocusEvent.augmentClass)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticFocusEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticFocusEvent.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticFocusEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticFocusEvent.release)
1.  number <span class="apidocSignatureSpan">react-dom.SyntheticFocusEvent.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticFocusEvent.</span>Interface
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticFocusEvent.</span>instancePool

#### [module react-dom.SyntheticFocusEvent.prototype](#apidoc.module.react-dom.SyntheticFocusEvent.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticFocusEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticFocusEvent.prototype.constructor)

#### [module react-dom.SyntheticInputEvent](#apidoc.module.react-dom.SyntheticInputEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticInputEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticInputEvent.SyntheticInputEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticInputEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticInputEvent.augmentClass)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticInputEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticInputEvent.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticInputEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticInputEvent.release)
1.  number <span class="apidocSignatureSpan">react-dom.SyntheticInputEvent.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticInputEvent.</span>Interface
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticInputEvent.</span>instancePool

#### [module react-dom.SyntheticInputEvent.prototype](#apidoc.module.react-dom.SyntheticInputEvent.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticInputEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticInputEvent.prototype.constructor)

#### [module react-dom.SyntheticKeyboardEvent](#apidoc.module.react-dom.SyntheticKeyboardEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticKeyboardEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticKeyboardEvent.SyntheticKeyboardEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticKeyboardEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticKeyboardEvent.augmentClass)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticKeyboardEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticKeyboardEvent.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticKeyboardEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticKeyboardEvent.release)
1.  number <span class="apidocSignatureSpan">react-dom.SyntheticKeyboardEvent.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticKeyboardEvent.</span>Interface
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticKeyboardEvent.</span>instancePool

#### [module react-dom.SyntheticKeyboardEvent.prototype](#apidoc.module.react-dom.SyntheticKeyboardEvent.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticKeyboardEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticKeyboardEvent.prototype.constructor)

#### [module react-dom.SyntheticMouseEvent](#apidoc.module.react-dom.SyntheticMouseEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticMouseEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticMouseEvent.SyntheticMouseEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticMouseEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticMouseEvent.augmentClass)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticMouseEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticMouseEvent.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticMouseEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticMouseEvent.release)
1.  number <span class="apidocSignatureSpan">react-dom.SyntheticMouseEvent.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticMouseEvent.</span>Interface
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticMouseEvent.</span>instancePool

#### [module react-dom.SyntheticMouseEvent.prototype](#apidoc.module.react-dom.SyntheticMouseEvent.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticMouseEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticMouseEvent.prototype.constructor)

#### [module react-dom.SyntheticTouchEvent](#apidoc.module.react-dom.SyntheticTouchEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticTouchEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticTouchEvent.SyntheticTouchEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticTouchEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticTouchEvent.augmentClass)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticTouchEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticTouchEvent.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticTouchEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticTouchEvent.release)
1.  number <span class="apidocSignatureSpan">react-dom.SyntheticTouchEvent.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticTouchEvent.</span>Interface
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticTouchEvent.</span>instancePool

#### [module react-dom.SyntheticTouchEvent.prototype](#apidoc.module.react-dom.SyntheticTouchEvent.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticTouchEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticTouchEvent.prototype.constructor)

#### [module react-dom.SyntheticTransitionEvent](#apidoc.module.react-dom.SyntheticTransitionEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticTransitionEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticTransitionEvent.SyntheticTransitionEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticTransitionEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticTransitionEvent.augmentClass)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticTransitionEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticTransitionEvent.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticTransitionEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticTransitionEvent.release)
1.  number <span class="apidocSignatureSpan">react-dom.SyntheticTransitionEvent.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticTransitionEvent.</span>Interface
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticTransitionEvent.</span>instancePool

#### [module react-dom.SyntheticTransitionEvent.prototype](#apidoc.module.react-dom.SyntheticTransitionEvent.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticTransitionEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticTransitionEvent.prototype.constructor)

#### [module react-dom.SyntheticUIEvent](#apidoc.module.react-dom.SyntheticUIEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticUIEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticUIEvent.SyntheticUIEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticUIEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticUIEvent.augmentClass)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticUIEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticUIEvent.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticUIEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticUIEvent.release)
1.  number <span class="apidocSignatureSpan">react-dom.SyntheticUIEvent.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticUIEvent.</span>Interface
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticUIEvent.</span>instancePool

#### [module react-dom.SyntheticUIEvent.prototype](#apidoc.module.react-dom.SyntheticUIEvent.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticUIEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticUIEvent.prototype.constructor)

#### [module react-dom.SyntheticWheelEvent](#apidoc.module.react-dom.SyntheticWheelEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>SyntheticWheelEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticWheelEvent.SyntheticWheelEvent)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticWheelEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticWheelEvent.augmentClass)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticWheelEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticWheelEvent.getPooled)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticWheelEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticWheelEvent.release)
1.  number <span class="apidocSignatureSpan">react-dom.SyntheticWheelEvent.</span>poolSize
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticWheelEvent.</span>Interface
1.  object <span class="apidocSignatureSpan">react-dom.SyntheticWheelEvent.</span>instancePool

#### [module react-dom.SyntheticWheelEvent.prototype](#apidoc.module.react-dom.SyntheticWheelEvent.prototype)
1.  [function <span class="apidocSignatureSpan">react-dom.SyntheticWheelEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticWheelEvent.prototype.constructor)

#### [module react-dom.TapEventPlugin](#apidoc.module.react-dom.TapEventPlugin)
1.  [function <span class="apidocSignatureSpan">react-dom.TapEventPlugin.</span>extractEvents (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.TapEventPlugin.extractEvents)
1.  number <span class="apidocSignatureSpan">react-dom.TapEventPlugin.</span>tapMoveThreshold
1.  object <span class="apidocSignatureSpan">react-dom.TapEventPlugin.</span>eventTypes

#### [module react-dom.TouchHistoryMath](#apidoc.module.react-dom.TouchHistoryMath)
1.  [function <span class="apidocSignatureSpan">react-dom.TouchHistoryMath.</span>centroidDimension (touchHistory, touchesChangedAfter, isXAxis, ofCurrent)](#apidoc.element.react-dom.TouchHistoryMath.centroidDimension)
1.  [function <span class="apidocSignatureSpan">react-dom.TouchHistoryMath.</span>currentCentroidX (touchHistory)](#apidoc.element.react-dom.TouchHistoryMath.currentCentroidX)
1.  [function <span class="apidocSignatureSpan">react-dom.TouchHistoryMath.</span>currentCentroidXOfTouchesChangedAfter (touchHistory, touchesChangedAfter)](#apidoc.element.react-dom.TouchHistoryMath.currentCentroidXOfTouchesChangedAfter)
1.  [function <span class="apidocSignatureSpan">react-dom.TouchHistoryMath.</span>currentCentroidY (touchHistory)](#apidoc.element.react-dom.TouchHistoryMath.currentCentroidY)
1.  [function <span class="apidocSignatureSpan">react-dom.TouchHistoryMath.</span>currentCentroidYOfTouchesChangedAfter (touchHistory, touchesChangedAfter)](#apidoc.element.react-dom.TouchHistoryMath.currentCentroidYOfTouchesChangedAfter)
1.  [function <span class="apidocSignatureSpan">react-dom.TouchHistoryMath.</span>previousCentroidXOfTouchesChangedAfter (touchHistory, touchesChangedAfter)](#apidoc.element.react-dom.TouchHistoryMath.previousCentroidXOfTouchesChangedAfter)
1.  [function <span class="apidocSignatureSpan">react-dom.TouchHistoryMath.</span>previousCentroidYOfTouchesChangedAfter (touchHistory, touchesChangedAfter)](#apidoc.element.react-dom.TouchHistoryMath.previousCentroidYOfTouchesChangedAfter)
1.  number <span class="apidocSignatureSpan">react-dom.TouchHistoryMath.</span>noCentroid

#### [module react-dom.Transaction](#apidoc.module.react-dom.Transaction)
1.  boolean <span class="apidocSignatureSpan">react-dom.Transaction.</span>_isInTransaction
1.  [function <span class="apidocSignatureSpan">react-dom.Transaction.</span>closeAll (startIndex)](#apidoc.element.react-dom.Transaction.closeAll)
1.  [function <span class="apidocSignatureSpan">react-dom.Transaction.</span>initializeAll (startIndex)](#apidoc.element.react-dom.Transaction.initializeAll)
1.  [function <span class="apidocSignatureSpan">react-dom.Transaction.</span>isInTransaction ()](#apidoc.element.react-dom.Transaction.isInTransaction)
1.  [function <span class="apidocSignatureSpan">react-dom.Transaction.</span>perform (method, scope, a, b, c, d, e, f)](#apidoc.element.react-dom.Transaction.perform)
1.  [function <span class="apidocSignatureSpan">react-dom.Transaction.</span>reinitializeTransaction ()](#apidoc.element.react-dom.Transaction.reinitializeTransaction)
1.  object <span class="apidocSignatureSpan">react-dom.Transaction.</span>getTransactionWrappers

#### [module react-dom.ViewportMetrics](#apidoc.module.react-dom.ViewportMetrics)
1.  [function <span class="apidocSignatureSpan">react-dom.ViewportMetrics.</span>refreshScrollValues (scrollPosition)](#apidoc.element.react-dom.ViewportMetrics.refreshScrollValues)
1.  number <span class="apidocSignatureSpan">react-dom.ViewportMetrics.</span>currentScrollLeft
1.  number <span class="apidocSignatureSpan">react-dom.ViewportMetrics.</span>currentScrollTop

#### [module react-dom.validateDOMNesting](#apidoc.module.react-dom.validateDOMNesting)
1.  [function <span class="apidocSignatureSpan">react-dom.</span>validateDOMNesting (childTag, childText, childInstance, ancestorInfo)](#apidoc.element.react-dom.validateDOMNesting.validateDOMNesting)
1.  [function <span class="apidocSignatureSpan">react-dom.validateDOMNesting.</span>isTagValidInContext (tag, ancestorInfo)](#apidoc.element.react-dom.validateDOMNesting.isTagValidInContext)
1.  [function <span class="apidocSignatureSpan">react-dom.validateDOMNesting.</span>updatedAncestorInfo (oldInfo, tag, instance)](#apidoc.element.react-dom.validateDOMNesting.updatedAncestorInfo)



# <a name="apidoc.module.react-dom"></a>[module react-dom](#apidoc.module.react-dom)

#### <a name="apidoc.element.react-dom.CallbackQueue"></a>[function <span class="apidocSignatureSpan">react-dom.</span>CallbackQueue (arg)](#apidoc.element.react-dom.CallbackQueue)
- description and source-code
```javascript
function CallbackQueue(arg) {
  _classCallCheck(this, CallbackQueue);

  this._callbacks = null;
  this._contexts = null;
  this._arg = arg;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.DOMLazyTree"></a>[function <span class="apidocSignatureSpan">react-dom.</span>DOMLazyTree (node)](#apidoc.element.react-dom.DOMLazyTree)
- description and source-code
```javascript
function DOMLazyTree(node) {
  return {
    node: node,
    children: [],
    html: null,
    text: null,
    toString: toString
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.FallbackCompositionState"></a>[function <span class="apidocSignatureSpan">react-dom.</span>FallbackCompositionState (root)](#apidoc.element.react-dom.FallbackCompositionState)
- description and source-code
```javascript
function FallbackCompositionState(root) {
  this._root = root;
  this._startText = this.getText();
  this._fallbackText = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ReactDOMComponent (element)](#apidoc.element.react-dom.ReactDOMComponent)
- description and source-code
```javascript
function ReactDOMComponent(element) {
  var tag = element.type;
  validateDangerousTag(tag);
  this._currentElement = element;
  this._tag = tag.toLowerCase();
  this._namespaceURI = null;
  this._renderedChildren = null;
  this._previousStyle = null;
  this._previousStyleCopy = null;
  this._hostNode = null;
  this._hostParent = null;
  this._rootNodeID = 0;
  this._domID = 0;
  this._hostContainerInfo = null;
  this._wrapperState = null;
  this._topLevelWrapper = null;
  this._flags = 0;
  if (process.env.NODE_ENV !== 'production') {
    this._ancestorInfo = null;
    setAndValidateContentChildDev.call(this, null);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactDOMEmptyComponent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ReactDOMEmptyComponent (instantiate)](#apidoc.element.react-dom.ReactDOMEmptyComponent)
- description and source-code
```javascript
ReactDOMEmptyComponent = function (instantiate) {
  // ReactCompositeComponent uses this:
  this._currentElement = null;
  // ReactDOMComponentTree uses these:
  this._hostNode = null;
  this._hostParent = null;
  this._hostContainerInfo = null;
  this._domID = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactDOMTextComponent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ReactDOMTextComponent (text)](#apidoc.element.react-dom.ReactDOMTextComponent)
- description and source-code
```javascript
ReactDOMTextComponent = function (text) {
  // TODO: This is really a ReactText (ReactNode), not a ReactElement
  this._currentElement = text;
  this._stringText = '' + text;
  // ReactDOMComponentTree uses these:
  this._hostNode = null;
  this._hostParent = null;

  // Properties
  this._domID = 0;
  this._mountIndex = 0;
  this._closingComment = null;
  this._commentNodes = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactReconcileTransaction"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ReactReconcileTransaction (useCreateElement)](#apidoc.element.react-dom.ReactReconcileTransaction)
- description and source-code
```javascript
function ReactReconcileTransaction(useCreateElement) {
  this.reinitializeTransaction();
  // Only server-side rendering really needs this option (see
  // 'ReactServerRendering'), but server-side uses
  // 'ReactServerRenderingTransaction' instead. This option is here so that it's
  // accessible and defaults to false when 'ReactDOMComponent' and
  // 'ReactDOMTextComponent' checks it in 'mountComponent'.'
  this.renderToStaticMarkup = false;
  this.reactMountReady = CallbackQueue.getPooled(null);
  this.useCreateElement = useCreateElement;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactServerRenderingTransaction"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ReactServerRenderingTransaction (renderToStaticMarkup)](#apidoc.element.react-dom.ReactServerRenderingTransaction)
- description and source-code
```javascript
function ReactServerRenderingTransaction(renderToStaticMarkup) {
  this.reinitializeTransaction();
  this.renderToStaticMarkup = renderToStaticMarkup;
  this.useCreateElement = false;
  this.updateQueue = new ReactServerUpdateQueue(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactServerUpdateQueue"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ReactServerUpdateQueue (transaction)](#apidoc.element.react-dom.ReactServerUpdateQueue)
- description and source-code
```javascript
function ReactServerUpdateQueue(transaction) {
  _classCallCheck(this, ReactServerUpdateQueue);

  this.transaction = transaction;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactShallowRenderer"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ReactShallowRenderer ()](#apidoc.element.react-dom.ReactShallowRenderer)
- description and source-code
```javascript
function ReactShallowRenderer() {
  _classCallCheck(this, ReactShallowRenderer);

  this._instance = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactSimpleEmptyComponent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ReactSimpleEmptyComponent (placeholderElement, instantiate)](#apidoc.element.react-dom.ReactSimpleEmptyComponent)
- description and source-code
```javascript
ReactSimpleEmptyComponent = function (placeholderElement, instantiate) {
  this._currentElement = null;
  this._renderedComponent = instantiate(placeholderElement);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactTestReconcileTransaction"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ReactTestReconcileTransaction (testOptions)](#apidoc.element.react-dom.ReactTestReconcileTransaction)
- description and source-code
```javascript
function ReactTestReconcileTransaction(testOptions) {
  this.reinitializeTransaction();
  this.testOptions = testOptions;
  this.reactMountReady = CallbackQueue.getPooled(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ResponderSyntheticEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ResponderSyntheticEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.ResponderSyntheticEvent)
- description and source-code
```javascript
function ResponderSyntheticEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticAnimationEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticAnimationEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticAnimationEvent)
- description and source-code
```javascript
function SyntheticAnimationEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticClipboardEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticClipboardEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticClipboardEvent)
- description and source-code
```javascript
function SyntheticClipboardEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticCompositionEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticCompositionEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticCompositionEvent)
- description and source-code
```javascript
function SyntheticCompositionEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticDragEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticDragEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticDragEvent)
- description and source-code
```javascript
function SyntheticDragEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticMouseEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticEvent {{signature}}](#apidoc.element.react-dom.SyntheticEvent)
- description and source-code
```javascript
n/a
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticFocusEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticFocusEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticFocusEvent)
- description and source-code
```javascript
function SyntheticFocusEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticUIEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticInputEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticInputEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticInputEvent)
- description and source-code
```javascript
function SyntheticInputEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticKeyboardEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticKeyboardEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticKeyboardEvent)
- description and source-code
```javascript
function SyntheticKeyboardEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticUIEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticMouseEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticMouseEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticMouseEvent)
- description and source-code
```javascript
function SyntheticMouseEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticUIEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticTouchEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticTouchEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticTouchEvent)
- description and source-code
```javascript
function SyntheticTouchEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticUIEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticTransitionEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticTransitionEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticTransitionEvent)
- description and source-code
```javascript
function SyntheticTransitionEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticUIEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticUIEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticUIEvent)
- description and source-code
```javascript
function SyntheticUIEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticWheelEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticWheelEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticWheelEvent)
- description and source-code
```javascript
function SyntheticWheelEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticMouseEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.findDOMNode"></a>[function <span class="apidocSignatureSpan">react-dom.</span>findDOMNode (componentOrElement)](#apidoc.element.react-dom.findDOMNode)
- description and source-code
```javascript
function findDOMNode(componentOrElement) {
  if (process.env.NODE_ENV !== 'production') {
    var owner = ReactCurrentOwner.current;
    if (owner !== null) {
      process.env.NODE_ENV !== 'production' ? warning(owner._warnedAboutRefsInRender, '%s is accessing findDOMNode inside its render
(). ' + 'render() should be a pure function of props and state. It should ' + 'never access something that requires stale data from
 the previous ' + 'render, such as refs. Move this logic to componentDidMount and ' + 'componentDidUpdate instead.', owner.getName
() || 'A component') : void 0;
      owner._warnedAboutRefsInRender = true;
    }
  }
  if (componentOrElement == null) {
    return null;
  }
  if (componentOrElement.nodeType === 1) {
    return componentOrElement;
  }

  var inst = ReactInstanceMap.get(componentOrElement);
  if (inst) {
    inst = getHostComponentFromComposite(inst);
    return inst ? ReactDOMComponentTree.getNodeFromInstance(inst) : null;
  }

  if (typeof componentOrElement.render === 'function') {
    !false ? process.env.NODE_ENV !== 'production' ? invariant(false, 'findDOMNode was called on an unmounted component.') : _prodInvariant
('44') : void 0;
  } else {
    !false ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Element appears to be neither ReactComponent nor DOMNode (
keys: %s)', Object.keys(componentOrElement)) : _prodInvariant('45', Object.keys(componentOrElement)) : void 0;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.render"></a>[function <span class="apidocSignatureSpan">react-dom.</span>render (nextElement, container, callback)](#apidoc.element.react-dom.render)
- description and source-code
```javascript
render = function (nextElement, container, callback) {
  return ReactMount._renderSubtreeIntoContainer(null, nextElement, container, callback);
}
```
- example usage
```shell
...

class MyComponent extends React.Component {
  render() {
    return <div>Hello World</div>;
  }
}

ReactDOM.render(<MyComponent />, node);
'''

### On the server

'''js
var React = require('react');
var ReactDOMServer = require('react-dom/server');
...
```

#### <a name="apidoc.element.react-dom.unmountComponentAtNode"></a>[function <span class="apidocSignatureSpan">react-dom.</span>unmountComponentAtNode (container)](#apidoc.element.react-dom.unmountComponentAtNode)
- description and source-code
```javascript
unmountComponentAtNode = function (container) {
  // Various parts of our code (such as ReactCompositeComponent's
  // _renderValidatedComponent) assume that calls to render aren't nested;
  // verify that that's the case. (Strictly speaking, unmounting won't cause a
  // render but we still don't expect to be in a render call here.)
  process.env.NODE_ENV !== 'production' ? warning(ReactCurrentOwner.current == null, 'unmountComponentAtNode(): Render methods should
 be a pure function ' + 'of props and state; triggering nested component updates from render ' + 'is not allowed. If necessary,
trigger nested updates in ' + 'componentDidUpdate. Check the render method of %s.', ReactCurrentOwner.current && ReactCurrentOwner
.current.getName() || 'ReactCompositeComponent') : void 0;

  !isValidContainer(container) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'unmountComponentAtNode(...): Target container
 is not a DOM element.') : _prodInvariant('40') : void 0;

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(!nodeIsRenderedByOtherInstance(container), 'unmountComponentAtNode(): The node
 you\'re attempting to unmount ' + 'was rendered by another copy of React.') : void 0;
  }

  var prevComponent = getTopLevelWrapperInContainer(container);
  if (!prevComponent) {
    // Check if the node being unmounted was rendered by React, but isn't a
    // root node.
    var containerHasNonRootReactChild = hasNonRootReactChild(container);

    // Check if the container itself is a React root node.
    var isContainerReactRoot = container.nodeType === 1 && container.hasAttribute(ROOT_ATTR_NAME);

    if (process.env.NODE_ENV !== 'production') {
      process.env.NODE_ENV !== 'production' ? warning(!containerHasNonRootReactChild, 'unmountComponentAtNode(): The node you\'re
 attempting to unmount ' + 'was rendered by React and is not a top-level container. %s', isContainerReactRoot ? 'You may have accidentally
 passed in a React root node instead ' + 'of its container.' : 'Instead, have the parent component update its state and ' + 'rerender
 in order to remove this component.') : void 0;
    }

    return false;
  }
  delete instancesByReactRootID[prevComponent._instance.rootID];
  ReactUpdates.batchedUpdates(unmountComponentFromNode, prevComponent, container, false);
  return true;
}
```
- example usage
```shell
...
    var publicInst = prevComponent._renderedComponent.getPublicInstance();
    var updatedCallback = callback && function () {
      callback.call(publicInst);
    };
    ReactMount._updateRootComponent(prevComponent, nextWrappedElement, nextContext, container, updatedCallback);
    return publicInst;
  } else {
    ReactMount.unmountComponentAtNode(container);
  }
}

var reactRootElement = getReactRootElementInContainer(container);
var containerHasReactMarkup = reactRootElement && !!internalGetID(reactRootElement);
var containerHasNonRootReactChild = hasNonRootReactChild(container);
...
```

#### <a name="apidoc.element.react-dom.unstable_batchedUpdates"></a>[function <span class="apidocSignatureSpan">react-dom.</span>unstable_batchedUpdates (callback, a, b, c, d, e)](#apidoc.element.react-dom.unstable_batchedUpdates)
- description and source-code
```javascript
function batchedUpdates(callback, a, b, c, d, e) {
  ensureInjected();
  return batchingStrategy.batchedUpdates(callback, a, b, c, d, e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.unstable_renderSubtreeIntoContainer"></a>[function <span class="apidocSignatureSpan">react-dom.</span>unstable_renderSubtreeIntoContainer (parentComponent, nextElement, container, callback)](#apidoc.element.react-dom.unstable_renderSubtreeIntoContainer)
- description and source-code
```javascript
unstable_renderSubtreeIntoContainer = function (parentComponent, nextElement, container, callback) {
  !(parentComponent != null && ReactInstanceMap.has(parentComponent)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '
parentComponent must be a valid React Component') : _prodInvariant('38') : void 0;
  return ReactMount._renderSubtreeIntoContainer(parentComponent, nextElement, container, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.validateDOMNesting"></a>[function <span class="apidocSignatureSpan">react-dom.</span>validateDOMNesting (childTag, childText, childInstance, ancestorInfo)](#apidoc.element.react-dom.validateDOMNesting)
- description and source-code
```javascript
validateDOMNesting = function (childTag, childText, childInstance, ancestorInfo) {
  ancestorInfo = ancestorInfo || emptyAncestorInfo;
  var parentInfo = ancestorInfo.current;
  var parentTag = parentInfo && parentInfo.tag;

  if (childText != null) {
    process.env.NODE_ENV !== 'production' ? warning(childTag == null, 'validateDOMNesting: when childText is passed, childTag should
 be null') : void 0;
    childTag = '#text';
  }

  var invalidParent = isTagValidWithParent(childTag, parentTag) ? null : parentInfo;
  var invalidAncestor = invalidParent ? null : findInvalidAncestorForTag(childTag, ancestorInfo);
  var problematic = invalidParent || invalidAncestor;

  if (problematic) {
    var ancestorTag = problematic.tag;
    var ancestorInstance = problematic.instance;

    var childOwner = childInstance && childInstance._currentElement._owner;
    var ancestorOwner = ancestorInstance && ancestorInstance._currentElement._owner;

    var childOwners = findOwnerStack(childOwner);
    var ancestorOwners = findOwnerStack(ancestorOwner);

    var minStackLen = Math.min(childOwners.length, ancestorOwners.length);
    var i;

    var deepestCommon = -1;
    for (i = 0; i < minStackLen; i++) {
      if (childOwners[i] === ancestorOwners[i]) {
        deepestCommon = i;
      } else {
        break;
      }
    }

    var UNKNOWN = '(unknown)';
    var childOwnerNames = childOwners.slice(deepestCommon + 1).map(function (inst) {
      return inst.getName() || UNKNOWN;
    });
    var ancestorOwnerNames = ancestorOwners.slice(deepestCommon + 1).map(function (inst) {
      return inst.getName() || UNKNOWN;
    });
    var ownerInfo = [].concat(
    // If the parent and child instances have a common owner ancestor, start
    // with that -- otherwise we just start with the parent's owners.
    deepestCommon !== -1 ? childOwners[deepestCommon].getName() || UNKNOWN : [], ancestorOwnerNames, ancestorTag,
    // If we're warning about an invalid (non-parent) ancestry, add '...'
    invalidAncestor ? ['...'] : [], childOwnerNames, childTag).join(' > ');

    var warnKey = !!invalidParent + '|' + childTag + '|' + ancestorTag + '|' + ownerInfo;
    if (didWarn[warnKey]) {
      return;
    }
    didWarn[warnKey] = true;

    var tagDisplayName = childTag;
    var whitespaceInfo = '';
    if (childTag === '#text') {
      if (/\S/.test(childText)) {
        tagDisplayName = 'Text nodes';
      } else {
        tagDisplayName = 'Whitespace text nodes';
        whitespaceInfo = ' Make sure you don\'t have any extra whitespace between tags on ' + 'each line of your source code.';
      }
    } else {
      tagDisplayName = '<' + childTag + '>';
    }

    if (invalidParent) {
      var info = '';
      if (ancestorTag === 'table' && childTag === 'tr') {
        info += ' Add a <tbody> to your code to match the DOM tree generated by ' + 'the browser.';
      }
      process.env.NODE_ENV !== 'production' ? warning(false, 'validateDOMNesting(...): %s cannot appear as a child of <%s>.%s ' + '
See %s.%s', tagDisplayName, ancestorTag, whitespaceInfo, ownerInfo, info) : void 0;
    } else {
      process.env.NODE_ENV !== 'production' ? warning(false, 'validateDOMNesting(...): %s cannot appear as a descendant of ' + '<%
s>. See %s.', tagDisplayName, ancestorTag, ownerInfo) : void 0;
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.AutoFocusUtils"></a>[module react-dom.AutoFocusUtils](#apidoc.module.react-dom.AutoFocusUtils)

#### <a name="apidoc.element.react-dom.AutoFocusUtils.focusDOMComponent"></a>[function <span class="apidocSignatureSpan">react-dom.AutoFocusUtils.</span>focusDOMComponent ()](#apidoc.element.react-dom.AutoFocusUtils.focusDOMComponent)
- description and source-code
```javascript
focusDOMComponent = function () {
  focusNode(ReactDOMComponentTree.getNodeFromInstance(this));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.BeforeInputEventPlugin"></a>[module react-dom.BeforeInputEventPlugin](#apidoc.module.react-dom.BeforeInputEventPlugin)

#### <a name="apidoc.element.react-dom.BeforeInputEventPlugin.extractEvents"></a>[function <span class="apidocSignatureSpan">react-dom.BeforeInputEventPlugin.</span>extractEvents (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.BeforeInputEventPlugin.extractEvents)
- description and source-code
```javascript
extractEvents = function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  return [extractCompositionEvent(topLevelType, targetInst, nativeEvent, nativeEventTarget), extractBeforeInputEvent(topLevelType
, targetInst, nativeEvent, nativeEventTarget)];
}
```
- example usage
```shell
...
extractEvents: function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  var events;
  var plugins = EventPluginRegistry.plugins;
  for (var i = 0; i < plugins.length; i++) {
    // Not every plugin in the ordering may be loaded at runtime.
    var possiblePlugin = plugins[i];
    if (possiblePlugin) {
      var extractedEvents = possiblePlugin.extractEvents(topLevelType, targetInst, nativeEvent, nativeEventTarget);
      if (extractedEvents) {
        events = accumulateInto(events, extractedEvents);
      }
    }
  }
  return events;
},
...
```



# <a name="apidoc.module.react-dom.CSSPropertyOperations"></a>[module react-dom.CSSPropertyOperations](#apidoc.module.react-dom.CSSPropertyOperations)

#### <a name="apidoc.element.react-dom.CSSPropertyOperations.createMarkupForStyles"></a>[function <span class="apidocSignatureSpan">react-dom.CSSPropertyOperations.</span>createMarkupForStyles (styles, component)](#apidoc.element.react-dom.CSSPropertyOperations.createMarkupForStyles)
- description and source-code
```javascript
createMarkupForStyles = function (styles, component) {
  var serialized = '';
  for (var styleName in styles) {
    if (!styles.hasOwnProperty(styleName)) {
      continue;
    }
    var styleValue = styles[styleName];
    if (process.env.NODE_ENV !== 'production') {
      warnValidStyle(styleName, styleValue, component);
    }
    if (styleValue != null) {
      serialized += processStyleName(styleName) + ':';
      serialized += dangerousStyleValue(styleName, styleValue, component) + ';';
    }
  }
  return serialized || null;
}
```
- example usage
```shell
...
  if (propValue) {
    if (process.env.NODE_ENV !== 'production') {
      // See '_updateDOMProperties'. style block
      this._previousStyle = propValue;
    }
    propValue = this._previousStyleCopy = _assign({}, props.style);
  }
  propValue = CSSPropertyOperations.createMarkupForStyles(propValue, this);
}
var markup = null;
if (this._tag != null && isCustomComponent(this._tag, props)) {
  if (!RESERVED_PROPS.hasOwnProperty(propKey)) {
    markup = DOMPropertyOperations.createMarkupForCustomAttribute(propKey, propValue);
  }
} else {
...
```

#### <a name="apidoc.element.react-dom.CSSPropertyOperations.setValueForStyles"></a>[function <span class="apidocSignatureSpan">react-dom.CSSPropertyOperations.</span>setValueForStyles (node, styles, component)](#apidoc.element.react-dom.CSSPropertyOperations.setValueForStyles)
- description and source-code
```javascript
setValueForStyles = function (node, styles, component) {
  if (process.env.NODE_ENV !== 'production') {
    ReactInstrumentation.debugTool.onHostOperation({
      instanceID: component._debugID,
      type: 'update styles',
      payload: styles
    });
  }

  var style = node.style;
  for (var styleName in styles) {
    if (!styles.hasOwnProperty(styleName)) {
      continue;
    }
    if (process.env.NODE_ENV !== 'production') {
      warnValidStyle(styleName, styles[styleName], component);
    }
    var styleValue = dangerousStyleValue(styleName, styles[styleName], component);
    if (styleName === 'float' || styleName === 'cssFloat') {
      styleName = styleFloatAccessor;
    }
    if (styleValue) {
      style[styleName] = styleValue;
    } else {
      var expansion = hasShorthandPropertyBug && CSSProperty.shorthandPropertyExpansions[styleName];
      if (expansion) {
        // Shorthand property that IE8 won't like unsetting, so unset each
        // component to placate it
        for (var individualStyleName in expansion) {
          style[individualStyleName] = '';
        }
      } else {
        style[styleName] = '';
      }
    }
  }
}
```
- example usage
```shell
...
        DOMPropertyOperations.setValueForProperty(node, propKey, nextProp);
      } else {
        DOMPropertyOperations.deleteValueForProperty(node, propKey);
      }
    }
  }
  if (styleUpdates) {
    CSSPropertyOperations.setValueForStyles(getNode(this), styleUpdates, this);
  }
},

/**
 * Reconciles the children with the various properties that affect the
 * children content.
 *
...
```



# <a name="apidoc.module.react-dom.CallbackQueue"></a>[module react-dom.CallbackQueue](#apidoc.module.react-dom.CallbackQueue)

#### <a name="apidoc.element.react-dom.CallbackQueue.CallbackQueue"></a>[function <span class="apidocSignatureSpan">react-dom.</span>CallbackQueue (arg)](#apidoc.element.react-dom.CallbackQueue.CallbackQueue)
- description and source-code
```javascript
function CallbackQueue(arg) {
  _classCallCheck(this, CallbackQueue);

  this._callbacks = null;
  this._contexts = null;
  this._arg = arg;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.CallbackQueue.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.CallbackQueue.</span>getPooled (copyFieldsFrom)](#apidoc.element.react-dom.CallbackQueue.getPooled)
- description and source-code
```javascript
getPooled = function (copyFieldsFrom) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, copyFieldsFrom);
    return instance;
  } else {
    return new Klass(copyFieldsFrom);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.CallbackQueue.release"></a>[function <span class="apidocSignatureSpan">react-dom.CallbackQueue.</span>release (instance)](#apidoc.element.react-dom.CallbackQueue.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.CallbackQueue.prototype"></a>[module react-dom.CallbackQueue.prototype](#apidoc.module.react-dom.CallbackQueue.prototype)

#### <a name="apidoc.element.react-dom.CallbackQueue.prototype.checkpoint"></a>[function <span class="apidocSignatureSpan">react-dom.CallbackQueue.prototype.</span>checkpoint ()](#apidoc.element.react-dom.CallbackQueue.prototype.checkpoint)
- description and source-code
```javascript
function checkpoint() {
  return this._callbacks ? this._callbacks.length : 0;
}
```
- example usage
```shell
...
  } else {
    return Component(publicProps, publicContext, updateQueue);
  }
},

performInitialMountWithErrorHandling: function (renderedElement, hostParent, hostContainerInfo, transaction, context) {
  var markup;
  var checkpoint = transaction.checkpoint();
  try {
    markup = this.performInitialMount(renderedElement, hostParent, hostContainerInfo, transaction, context);
  } catch (e) {
    // Roll back to checkpoint, handle error (which may add items to the transaction), and take a new checkpoint
    transaction.rollback(checkpoint);
    this._instance.unstable_handleError(e);
    if (this._pendingStateQueue) {
...
```

#### <a name="apidoc.element.react-dom.CallbackQueue.prototype.destructor"></a>[function <span class="apidocSignatureSpan">react-dom.CallbackQueue.prototype.</span>destructor ()](#apidoc.element.react-dom.CallbackQueue.prototype.destructor)
- description and source-code
```javascript
function destructor() {
  this.reset();
}
```
- example usage
```shell
...
    return new Klass(a1, a2, a3, a4);
  }
};

var standardReleaser = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
};

var DEFAULT_POOL_SIZE = 10;
var DEFAULT_POOLER = oneArgumentPooler;
...
```

#### <a name="apidoc.element.react-dom.CallbackQueue.prototype.enqueue"></a>[function <span class="apidocSignatureSpan">react-dom.CallbackQueue.prototype.</span>enqueue (callback, context)](#apidoc.element.react-dom.CallbackQueue.prototype.enqueue)
- description and source-code
```javascript
function enqueue(callback, context) {
  this._callbacks = this._callbacks || [];
  this._callbacks.push(callback);
  this._contexts = this._contexts || [];
  this._contexts.push(context);
}
```
- example usage
```shell
...
  markup = this.performInitialMountWithErrorHandling(renderedElement, hostParent, hostContainerInfo, transaction, context);
} else {
  markup = this.performInitialMount(renderedElement, hostParent, hostContainerInfo, transaction, context);
}

if (inst.componentDidMount) {
  if (process.env.NODE_ENV !== 'production') {
    transaction.getReactMountReady().enqueue(function () {
      measureLifeCyclePerf(function () {
        return inst.componentDidMount();
      }, _this._debugID, 'componentDidMount');
    });
  } else {
    transaction.getReactMountReady().enqueue(inst.componentDidMount, inst);
  }
...
```

#### <a name="apidoc.element.react-dom.CallbackQueue.prototype.notifyAll"></a>[function <span class="apidocSignatureSpan">react-dom.CallbackQueue.prototype.</span>notifyAll ()](#apidoc.element.react-dom.CallbackQueue.prototype.notifyAll)
- description and source-code
```javascript
function notifyAll() {
  var callbacks = this._callbacks;
  var contexts = this._contexts;
  var arg = this._arg;
  if (callbacks && contexts) {
    !(callbacks.length === contexts.length) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Mismatched list of contexts
 in callback queue') : _prodInvariant('24') : void 0;
    this._callbacks = null;
    this._contexts = null;
    for (var i = 0; i < callbacks.length; i++) {
      callbacks[i].call(contexts[i], arg);
    }
    callbacks.length = 0;
    contexts.length = 0;
  }
}
```
- example usage
```shell
...
   this.reactMountReady.reset();
 },

 /**
  * After DOM is flushed, invoke all registered 'onDOMReady' callbacks.
  */
 close: function () {
   this.reactMountReady.notifyAll();
 }
};

/**
* Executed within the scope of the 'Transaction' instance. Consider these as
* being member methods, but with an implied ordering while being isolated from
* each other.
...
```

#### <a name="apidoc.element.react-dom.CallbackQueue.prototype.reset"></a>[function <span class="apidocSignatureSpan">react-dom.CallbackQueue.prototype.</span>reset ()](#apidoc.element.react-dom.CallbackQueue.prototype.reset)
- description and source-code
```javascript
function reset() {
  this._callbacks = null;
  this._contexts = null;
}
```
- example usage
```shell
...

  /**
   * 'PooledClass' looks for this.
   */


  CallbackQueue.prototype.destructor = function destructor() {
    this.reset();
  };

  return CallbackQueue;
}();

module.exports = PooledClass.addPoolingTo(CallbackQueue);
...
```

#### <a name="apidoc.element.react-dom.CallbackQueue.prototype.rollback"></a>[function <span class="apidocSignatureSpan">react-dom.CallbackQueue.prototype.</span>rollback (len)](#apidoc.element.react-dom.CallbackQueue.prototype.rollback)
- description and source-code
```javascript
function rollback(len) {
  if (this._callbacks && this._contexts) {
    this._callbacks.length = len;
    this._contexts.length = len;
  }
}
```
- example usage
```shell
...
  performInitialMountWithErrorHandling: function (renderedElement, hostParent, hostContainerInfo, transaction, context) {
    var markup;
    var checkpoint = transaction.checkpoint();
    try {
markup = this.performInitialMount(renderedElement, hostParent, hostContainerInfo, transaction, context);
    } catch (e) {
// Roll back to checkpoint, handle error (which may add items to the transaction), and take a new checkpoint
transaction.rollback(checkpoint);
this._instance.unstable_handleError(e);
if (this._pendingStateQueue) {
  this._instance.state = this._processPendingState(this._instance.props, this._instance.context);
}
checkpoint = transaction.checkpoint();

this._renderedComponent.unmountComponent(true);
...
```



# <a name="apidoc.module.react-dom.ChangeEventPlugin"></a>[module react-dom.ChangeEventPlugin](#apidoc.module.react-dom.ChangeEventPlugin)

#### <a name="apidoc.element.react-dom.ChangeEventPlugin.extractEvents"></a>[function <span class="apidocSignatureSpan">react-dom.ChangeEventPlugin.</span>extractEvents (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.ChangeEventPlugin.extractEvents)
- description and source-code
```javascript
extractEvents = function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  var targetNode = targetInst ? ReactDOMComponentTree.getNodeFromInstance(targetInst) : window;

  var getTargetInstFunc, handleEventFunc;
  if (shouldUseChangeEvent(targetNode)) {
    if (doesChangeEventBubble) {
      getTargetInstFunc = getTargetInstForChangeEvent;
    } else {
      handleEventFunc = handleEventsForChangeEventIE8;
    }
  } else if (isTextInputElement(targetNode)) {
    if (isInputEventSupported) {
      getTargetInstFunc = getTargetInstForInputEvent;
    } else {
      getTargetInstFunc = getTargetInstForInputEventIE;
      handleEventFunc = handleEventsForInputEventIE;
    }
  } else if (shouldUseClickEvent(targetNode)) {
    getTargetInstFunc = getTargetInstForClickEvent;
  }

  if (getTargetInstFunc) {
    var inst = getTargetInstFunc(topLevelType, targetInst);
    if (inst) {
      var event = SyntheticEvent.getPooled(eventTypes.change, inst, nativeEvent, nativeEventTarget);
      event.type = 'change';
      EventPropagators.accumulateTwoPhaseDispatches(event);
      return event;
    }
  }

  if (handleEventFunc) {
    handleEventFunc(topLevelType, targetNode, targetInst);
  }

  // When blurring, set the value attribute for number inputs
  if (topLevelType === 'topBlur') {
    handleControlledInputBlur(targetInst, targetNode);
  }
}
```
- example usage
```shell
...
extractEvents: function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  var events;
  var plugins = EventPluginRegistry.plugins;
  for (var i = 0; i < plugins.length; i++) {
    // Not every plugin in the ordering may be loaded at runtime.
    var possiblePlugin = plugins[i];
    if (possiblePlugin) {
      var extractedEvents = possiblePlugin.extractEvents(topLevelType, targetInst, nativeEvent, nativeEventTarget);
      if (extractedEvents) {
        events = accumulateInto(events, extractedEvents);
      }
    }
  }
  return events;
},
...
```



# <a name="apidoc.module.react-dom.DOMChildrenOperations"></a>[module react-dom.DOMChildrenOperations](#apidoc.module.react-dom.DOMChildrenOperations)

#### <a name="apidoc.element.react-dom.DOMChildrenOperations.dangerouslyReplaceNodeWithMarkup"></a>[function <span class="apidocSignatureSpan">react-dom.DOMChildrenOperations.</span>dangerouslyReplaceNodeWithMarkup (oldChild, markup, prevInstance)](#apidoc.element.react-dom.DOMChildrenOperations.dangerouslyReplaceNodeWithMarkup)
- description and source-code
```javascript
dangerouslyReplaceNodeWithMarkup = function (oldChild, markup, prevInstance) {
  Danger.dangerouslyReplaceNodeWithMarkup(oldChild, markup);
  if (prevInstance._debugID !== 0) {
    ReactInstrumentation.debugTool.onHostOperation({
      instanceID: prevInstance._debugID,
      type: 'replace with',
      payload: markup.toString()
    });
  } else {
    var nextInstance = ReactDOMComponentTree.getInstanceFromNode(markup.node);
    if (nextInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onHostOperation({
        instanceID: nextInstance._debugID,
        type: 'mount',
        payload: markup.toString()
      });
    }
  }
}
```
- example usage
```shell
...
  });
}
}

var dangerouslyReplaceNodeWithMarkup = Danger.dangerouslyReplaceNodeWithMarkup;
if (process.env.NODE_ENV !== 'production') {
dangerouslyReplaceNodeWithMarkup = function (oldChild, markup, prevInstance) {
  Danger.dangerouslyReplaceNodeWithMarkup(oldChild, markup);
  if (prevInstance._debugID !== 0) {
    ReactInstrumentation.debugTool.onHostOperation({
      instanceID: prevInstance._debugID,
      type: 'replace with',
      payload: markup.toString()
    });
  } else {
...
```

#### <a name="apidoc.element.react-dom.DOMChildrenOperations.processUpdates"></a>[function <span class="apidocSignatureSpan">react-dom.DOMChildrenOperations.</span>processUpdates (parentNode, updates)](#apidoc.element.react-dom.DOMChildrenOperations.processUpdates)
- description and source-code
```javascript
processUpdates = function (parentNode, updates) {
  if (process.env.NODE_ENV !== 'production') {
    var parentNodeDebugID = ReactDOMComponentTree.getInstanceFromNode(parentNode)._debugID;
  }

  for (var k = 0; k < updates.length; k++) {
    var update = updates[k];
    switch (update.type) {
      case 'INSERT_MARKUP':
        insertLazyTreeChildAt(parentNode, update.content, getNodeAfter(parentNode, update.afterNode));
        if (process.env.NODE_ENV !== 'production') {
          ReactInstrumentation.debugTool.onHostOperation({
            instanceID: parentNodeDebugID,
            type: 'insert child',
            payload: { toIndex: update.toIndex, content: update.content.toString() }
          });
        }
        break;
      case 'MOVE_EXISTING':
        moveChild(parentNode, update.fromNode, getNodeAfter(parentNode, update.afterNode));
        if (process.env.NODE_ENV !== 'production') {
          ReactInstrumentation.debugTool.onHostOperation({
            instanceID: parentNodeDebugID,
            type: 'move child',
            payload: { fromIndex: update.fromIndex, toIndex: update.toIndex }
          });
        }
        break;
      case 'SET_MARKUP':
        setInnerHTML(parentNode, update.content);
        if (process.env.NODE_ENV !== 'production') {
          ReactInstrumentation.debugTool.onHostOperation({
            instanceID: parentNodeDebugID,
            type: 'replace children',
            payload: update.content.toString()
          });
        }
        break;
      case 'TEXT_CONTENT':
        setTextContent(parentNode, update.content);
        if (process.env.NODE_ENV !== 'production') {
          ReactInstrumentation.debugTool.onHostOperation({
            instanceID: parentNodeDebugID,
            type: 'replace text',
            payload: update.content.toString()
          });
        }
        break;
      case 'REMOVE_NODE':
        removeChild(parentNode, update.fromNode);
        if (process.env.NODE_ENV !== 'production') {
          ReactInstrumentation.debugTool.onHostOperation({
            instanceID: parentNodeDebugID,
            type: 'remove child',
            payload: { fromIndex: update.fromIndex }
          });
        }
        break;
    }
  }
}
```
- example usage
```shell
...
   * Updates a component's children by processing a series of updates.
   *
   * @param {array<object>} updates List of update configurations.
   * @internal
   */
  dangerouslyProcessChildrenUpdates: function (parentInst, updates) {
    var node = ReactDOMComponentTree.getNodeFromInstance(parentInst);
    DOMChildrenOperations.processUpdates(node, updates);
  }
};

module.exports = ReactDOMIDOperations;
...
```

#### <a name="apidoc.element.react-dom.DOMChildrenOperations.replaceDelimitedText"></a>[function <span class="apidocSignatureSpan">react-dom.DOMChildrenOperations.</span>replaceDelimitedText (openingComment, closingComment, stringText)](#apidoc.element.react-dom.DOMChildrenOperations.replaceDelimitedText)
- description and source-code
```javascript
function replaceDelimitedText(openingComment, closingComment, stringText) {
  var parentNode = openingComment.parentNode;
  var nodeAfterComment = openingComment.nextSibling;
  if (nodeAfterComment === closingComment) {
    // There are no text nodes between the opening and closing comments; insert
    // a new one if stringText isn't empty.
    if (stringText) {
      insertChildAt(parentNode, document.createTextNode(stringText), nodeAfterComment);
    }
  } else {
    if (stringText) {
      // Set the text content of the first node after the opening comment, and
      // remove all following nodes up until the closing comment.
      setTextContent(nodeAfterComment, stringText);
      removeDelimitedText(parentNode, nodeAfterComment, closingComment);
    } else {
      removeDelimitedText(parentNode, openingComment, closingComment);
    }
  }

  if (process.env.NODE_ENV !== 'production') {
    ReactInstrumentation.debugTool.onHostOperation({
      instanceID: ReactDOMComponentTree.getInstanceFromNode(openingComment)._debugID,
      type: 'replace text',
      payload: stringText
    });
  }
}
```
- example usage
```shell
...
    var nextStringText = '' + nextText;
    if (nextStringText !== this._stringText) {
      // TODO: Save this as pending props and use performUpdateIfNecessary
      // and/or updateComponent to do the actual update for consistency with
      // other component types?
      this._stringText = nextStringText;
      var commentNodes = this.getHostNode();
      DOMChildrenOperations.replaceDelimitedText(commentNodes[0], commentNodes[1], nextStringText);
    }
  }
},

getHostNode: function () {
  var hostNode = this._commentNodes;
  if (hostNode) {
...
```



# <a name="apidoc.module.react-dom.DOMLazyTree"></a>[module react-dom.DOMLazyTree](#apidoc.module.react-dom.DOMLazyTree)

#### <a name="apidoc.element.react-dom.DOMLazyTree.DOMLazyTree"></a>[function <span class="apidocSignatureSpan">react-dom.</span>DOMLazyTree (node)](#apidoc.element.react-dom.DOMLazyTree.DOMLazyTree)
- description and source-code
```javascript
function DOMLazyTree(node) {
  return {
    node: node,
    children: [],
    html: null,
    text: null,
    toString: toString
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.DOMLazyTree.insertTreeBefore"></a>[function <span class="apidocSignatureSpan">react-dom.DOMLazyTree.</span>insertTreeBefore (parentNode, tree, referenceNode)](#apidoc.element.react-dom.DOMLazyTree.insertTreeBefore)
- description and source-code
```javascript
insertTreeBefore = function (parentNode, tree, referenceNode) {
  // DocumentFragments aren't actually part of the DOM after insertion so
  // appending children won't update the DOM. We need to ensure the fragment
  // is properly populated first, breaking out of our lazy approach for just
  // this level. Also, some <object> plugins (like Flash Player) will read
  // <param> nodes immediately upon insertion into the DOM, so <object>
  // must also be populated prior to insertion into the DOM.
  if (tree.node.nodeType === DOCUMENT_FRAGMENT_NODE_TYPE || tree.node.nodeType === ELEMENT_NODE_TYPE && tree.node.nodeName.toLowerCase
() === 'object' && (tree.node.namespaceURI == null || tree.node.namespaceURI === DOMNamespaces.html)) {
    insertTreeChildren(tree);
    parentNode.insertBefore(tree.node, referenceNode);
  } else {
    parentNode.insertBefore(tree.node, referenceNode);
    insertTreeChildren(tree);
  }
}
```
- example usage
```shell
...
// We rely exclusively on 'insertBefore(node, null)' instead of also using
// 'appendChild(node)'. (Using 'undefined' is not allowed by all browsers so
// we are careful to use 'null'.)
parentNode.insertBefore(childNode, referenceNode);
});

function insertLazyTreeChildAt(parentNode, childTree, referenceNode) {
DOMLazyTree.insertTreeBefore(parentNode, childTree, referenceNode);
}

function moveChild(parentNode, childNode, referenceNode) {
if (Array.isArray(childNode)) {
  moveDelimitedText(parentNode, childNode[0], childNode[1], referenceNode);
} else {
  insertChildAt(parentNode, childNode, referenceNode);
...
```

#### <a name="apidoc.element.react-dom.DOMLazyTree.queueChild"></a>[function <span class="apidocSignatureSpan">react-dom.DOMLazyTree.</span>queueChild (parentTree, childTree)](#apidoc.element.react-dom.DOMLazyTree.queueChild)
- description and source-code
```javascript
function queueChild(parentTree, childTree) {
  if (enableLazy) {
    parentTree.children.push(childTree);
  } else {
    parentTree.node.appendChild(childTree.node);
  }
}
```
- example usage
```shell
...
          setAndValidateContentChildDev.call(this, contentToUse);
        }
        DOMLazyTree.queueText(lazyTree, contentToUse);
      }
    } else if (childrenToUse != null) {
      var mountImages = this.mountChildren(childrenToUse, transaction, context);
      for (var i = 0; i < mountImages.length; i++) {
        DOMLazyTree.queueChild(lazyTree, mountImages[i]);
      }
    }
  }
},

/**
 * Receives a next element and updates the component.
...
```

#### <a name="apidoc.element.react-dom.DOMLazyTree.queueHTML"></a>[function <span class="apidocSignatureSpan">react-dom.DOMLazyTree.</span>queueHTML (tree, html)](#apidoc.element.react-dom.DOMLazyTree.queueHTML)
- description and source-code
```javascript
function queueHTML(tree, html) {
  if (enableLazy) {
    tree.html = html;
  } else {
    setInnerHTML(tree.node, html);
  }
}
```
- example usage
```shell
...
},

_createInitialChildren: function (transaction, props, context, lazyTree) {
  // Intentional use of != to avoid catching zero/false.
  var innerHTML = props.dangerouslySetInnerHTML;
  if (innerHTML != null) {
    if (innerHTML.__html != null) {
      DOMLazyTree.queueHTML(lazyTree, innerHTML.__html);
    }
  } else {
    var contentToUse = CONTENT_TYPES[typeof props.children] ? props.children : null;
    var childrenToUse = contentToUse != null ? null : props.children;
    // TODO: Validate that text is allowed as a child of this node
    if (contentToUse != null) {
      // Avoid setting textContent when the text is empty. In IE11 setting
...
```

#### <a name="apidoc.element.react-dom.DOMLazyTree.queueText"></a>[function <span class="apidocSignatureSpan">react-dom.DOMLazyTree.</span>queueText (tree, text)](#apidoc.element.react-dom.DOMLazyTree.queueText)
- description and source-code
```javascript
function queueText(tree, text) {
  if (enableLazy) {
    tree.text = text;
  } else {
    setTextContent(tree.node, text);
  }
}
```
- example usage
```shell
...
  // textContent on a text area will cause the placeholder to not
  // show within the textarea until it has been focused and blurred again.
  // https://github.com/facebook/react/issues/6731#issuecomment-254874553
  if (contentToUse !== '') {
    if (process.env.NODE_ENV !== 'production') {
      setAndValidateContentChildDev.call(this, contentToUse);
    }
    DOMLazyTree.queueText(lazyTree, contentToUse);
  }
} else if (childrenToUse != null) {
  var mountImages = this.mountChildren(childrenToUse, transaction, context);
  for (var i = 0; i < mountImages.length; i++) {
    DOMLazyTree.queueChild(lazyTree, mountImages[i]);
  }
}
...
```

#### <a name="apidoc.element.react-dom.DOMLazyTree.replaceChildWithTree"></a>[function <span class="apidocSignatureSpan">react-dom.DOMLazyTree.</span>replaceChildWithTree (oldNode, newTree)](#apidoc.element.react-dom.DOMLazyTree.replaceChildWithTree)
- description and source-code
```javascript
function replaceChildWithTree(oldNode, newTree) {
  oldNode.parentNode.replaceChild(newTree.node, oldNode);
  insertTreeChildren(newTree);
}
```
- example usage
```shell
...
    !markup ? process.env.NODE_ENV !== 'production' ? invariant(false, 'dangerouslyReplaceNodeWithMarkup(...): Missing markup.') :
_prodInvariant('57') : void 0;
    !(oldChild.nodeName !== 'HTML') ? process.env.NODE_ENV !== 'production' ? invariant(false, 'dangerouslyReplaceNodeWithMarkup
(...): Cannot replace markup of the <html> node. This is because browser quirks make this unreliable and/or slow. If you want to
 render to the root you must use server rendering. See ReactDOMServer.renderToString().') : _prodInvariant('58') : void 0;

    if (typeof markup === 'string') {
      var newChild = createNodesFromMarkup(markup, emptyFunction)[0];
      oldChild.parentNode.replaceChild(newChild, oldChild);
    } else {
      DOMLazyTree.replaceChildWithTree(oldChild, markup);
    }
  }

};

module.exports = Danger;
...
```



# <a name="apidoc.module.react-dom.DOMProperty"></a>[module react-dom.DOMProperty](#apidoc.module.react-dom.DOMProperty)

#### <a name="apidoc.element.react-dom.DOMProperty.isCustomAttribute"></a>[function <span class="apidocSignatureSpan">react-dom.DOMProperty.</span>isCustomAttribute (attributeName)](#apidoc.element.react-dom.DOMProperty.isCustomAttribute)
- description and source-code
```javascript
isCustomAttribute = function (attributeName) {
  for (var i = 0; i < DOMProperty._isCustomAttributeFunctions.length; i++) {
    var isCustomAttributeFn = DOMProperty._isCustomAttributeFunctions[i];
    if (isCustomAttributeFn(attributeName)) {
      return true;
    }
  }
  return false;
}
```
- example usage
```shell
...
      return '';
    }
    var attributeName = propertyInfo.attributeName;
    if (propertyInfo.hasBooleanValue || propertyInfo.hasOverloadedBooleanValue && value === true) {
      return attributeName + '=""';
    }
    return attributeName + '=' + quoteAttributeValueForBrowser(value);
  } else if (DOMProperty.isCustomAttribute(name)) {
    if (value == null) {
      return '';
    }
    return name + '=' + quoteAttributeValueForBrowser(value);
  }
  return null;
},
...
```



# <a name="apidoc.module.react-dom.DOMPropertyOperations"></a>[module react-dom.DOMPropertyOperations](#apidoc.module.react-dom.DOMPropertyOperations)

#### <a name="apidoc.element.react-dom.DOMPropertyOperations.createMarkupForCustomAttribute"></a>[function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>createMarkupForCustomAttribute (name, value)](#apidoc.element.react-dom.DOMPropertyOperations.createMarkupForCustomAttribute)
- description and source-code
```javascript
createMarkupForCustomAttribute = function (name, value) {
  if (!isAttributeNameSafe(name) || value == null) {
    return '';
  }
  return name + '=' + quoteAttributeValueForBrowser(value);
}
```
- example usage
```shell
...
    propValue = this._previousStyleCopy = _assign({}, props.style);
  }
  propValue = CSSPropertyOperations.createMarkupForStyles(propValue, this);
}
var markup = null;
if (this._tag != null && isCustomComponent(this._tag, props)) {
  if (!RESERVED_PROPS.hasOwnProperty(propKey)) {
    markup = DOMPropertyOperations.createMarkupForCustomAttribute(propKey, propValue);
  }
} else {
  markup = DOMPropertyOperations.createMarkupForProperty(propKey, propValue);
}
if (markup) {
  ret += ' ' + markup;
}
...
```

#### <a name="apidoc.element.react-dom.DOMPropertyOperations.createMarkupForID"></a>[function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>createMarkupForID (id)](#apidoc.element.react-dom.DOMPropertyOperations.createMarkupForID)
- description and source-code
```javascript
createMarkupForID = function (id) {
  return DOMProperty.ID_ATTRIBUTE_NAME + '=' + quoteAttributeValueForBrowser(id);
}
```
- example usage
```shell
...
  if (transaction.renderToStaticMarkup) {
    return ret;
  }

  if (!this._hostParent) {
    ret += ' ' + DOMPropertyOperations.createMarkupForRoot();
  }
  ret += ' ' + DOMPropertyOperations.createMarkupForID(this._domID);
  return ret;
},

/**
 * Creates markup for the content between the tags.
 *
 * @private
...
```

#### <a name="apidoc.element.react-dom.DOMPropertyOperations.createMarkupForProperty"></a>[function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>createMarkupForProperty (name, value)](#apidoc.element.react-dom.DOMPropertyOperations.createMarkupForProperty)
- description and source-code
```javascript
createMarkupForProperty = function (name, value) {
  var propertyInfo = DOMProperty.properties.hasOwnProperty(name) ? DOMProperty.properties[name] : null;
  if (propertyInfo) {
    if (shouldIgnoreValue(propertyInfo, value)) {
      return '';
    }
    var attributeName = propertyInfo.attributeName;
    if (propertyInfo.hasBooleanValue || propertyInfo.hasOverloadedBooleanValue && value === true) {
      return attributeName + '=""';
    }
    return attributeName + '=' + quoteAttributeValueForBrowser(value);
  } else if (DOMProperty.isCustomAttribute(name)) {
    if (value == null) {
      return '';
    }
    return name + '=' + quoteAttributeValueForBrowser(value);
  }
  return null;
}
```
- example usage
```shell
...
    }
    var markup = null;
    if (this._tag != null && isCustomComponent(this._tag, props)) {
      if (!RESERVED_PROPS.hasOwnProperty(propKey)) {
        markup = DOMPropertyOperations.createMarkupForCustomAttribute(propKey, propValue);
      }
    } else {
      markup = DOMPropertyOperations.createMarkupForProperty(propKey, propValue);
    }
    if (markup) {
      ret += ' ' + markup;
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.DOMPropertyOperations.createMarkupForRoot"></a>[function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>createMarkupForRoot ()](#apidoc.element.react-dom.DOMPropertyOperations.createMarkupForRoot)
- description and source-code
```javascript
createMarkupForRoot = function () {
  return DOMProperty.ROOT_ATTRIBUTE_NAME + '=""';
}
```
- example usage
```shell
...
  // For static pages, no need to put React ID and checksum. Saves lots of
  // bytes.
  if (transaction.renderToStaticMarkup) {
    return ret;
  }

  if (!this._hostParent) {
    ret += ' ' + DOMPropertyOperations.createMarkupForRoot();
  }
  ret += ' ' + DOMPropertyOperations.createMarkupForID(this._domID);
  return ret;
},

/**
 * Creates markup for the content between the tags.
...
```

#### <a name="apidoc.element.react-dom.DOMPropertyOperations.deleteValueForAttribute"></a>[function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>deleteValueForAttribute (node, name)](#apidoc.element.react-dom.DOMPropertyOperations.deleteValueForAttribute)
- description and source-code
```javascript
deleteValueForAttribute = function (node, name) {
  node.removeAttribute(name);
  if (process.env.NODE_ENV !== 'production') {
    ReactInstrumentation.debugTool.onHostOperation({
      instanceID: ReactDOMComponentTree.getInstanceFromNode(node)._debugID,
      type: 'remove attribute',
      payload: name
    });
  }
}
```
- example usage
```shell
...
      // Only call deleteListener if there was a listener previously or
      // else willDeleteListener gets called when there wasn't actually a
      // listener (e.g., onClick={null})
      deleteListener(this, propKey);
    }
  } else if (isCustomComponent(this._tag, lastProps)) {
    if (!RESERVED_PROPS.hasOwnProperty(propKey)) {
      DOMPropertyOperations.deleteValueForAttribute(getNode(this), propKey);
    }
  } else if (DOMProperty.properties[propKey] || DOMProperty.isCustomAttribute(propKey)) {
    DOMPropertyOperations.deleteValueForProperty(getNode(this), propKey);
  }
}
for (propKey in nextProps) {
  var nextProp = nextProps[propKey];
...
```

#### <a name="apidoc.element.react-dom.DOMPropertyOperations.deleteValueForProperty"></a>[function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>deleteValueForProperty (node, name)](#apidoc.element.react-dom.DOMPropertyOperations.deleteValueForProperty)
- description and source-code
```javascript
deleteValueForProperty = function (node, name) {
  var propertyInfo = DOMProperty.properties.hasOwnProperty(name) ? DOMProperty.properties[name] : null;
  if (propertyInfo) {
    var mutationMethod = propertyInfo.mutationMethod;
    if (mutationMethod) {
      mutationMethod(node, undefined);
    } else if (propertyInfo.mustUseProperty) {
      var propName = propertyInfo.propertyName;
      if (propertyInfo.hasBooleanValue) {
        node[propName] = false;
      } else {
        node[propName] = '';
      }
    } else {
      node.removeAttribute(propertyInfo.attributeName);
    }
  } else if (DOMProperty.isCustomAttribute(name)) {
    node.removeAttribute(name);
  }

  if (process.env.NODE_ENV !== 'production') {
    ReactInstrumentation.debugTool.onHostOperation({
      instanceID: ReactDOMComponentTree.getInstanceFromNode(node)._debugID,
      type: 'remove attribute',
      payload: name
    });
  }
}
```
- example usage
```shell
...
  setValueForProperty: function (node, name, value) {
var propertyInfo = DOMProperty.properties.hasOwnProperty(name) ? DOMProperty.properties[name] : null;
if (propertyInfo) {
  var mutationMethod = propertyInfo.mutationMethod;
  if (mutationMethod) {
    mutationMethod(node, value);
  } else if (shouldIgnoreValue(propertyInfo, value)) {
    this.deleteValueForProperty(node, name);
    return;
  } else if (propertyInfo.mustUseProperty) {
    // Contrary to 'setAttribute', object properties are properly
    // 'toString'ed by IE8/9.
    node[propertyInfo.propertyName] = value;
  } else {
    var attributeName = propertyInfo.attributeName;
...
```

#### <a name="apidoc.element.react-dom.DOMPropertyOperations.setAttributeForID"></a>[function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>setAttributeForID (node, id)](#apidoc.element.react-dom.DOMPropertyOperations.setAttributeForID)
- description and source-code
```javascript
setAttributeForID = function (node, id) {
  node.setAttribute(DOMProperty.ID_ATTRIBUTE_NAME, id);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.DOMPropertyOperations.setAttributeForRoot"></a>[function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>setAttributeForRoot (node)](#apidoc.element.react-dom.DOMPropertyOperations.setAttributeForRoot)
- description and source-code
```javascript
setAttributeForRoot = function (node) {
  node.setAttribute(DOMProperty.ROOT_ATTRIBUTE_NAME, '');
}
```
- example usage
```shell
...
    }
  } else {
    el = ownerDocument.createElementNS(namespaceURI, this._currentElement.type);
  }
  ReactDOMComponentTree.precacheNode(this, el);
  this._flags |= Flags.hasCachedChildNodes;
  if (!this._hostParent) {
    DOMPropertyOperations.setAttributeForRoot(el);
  }
  this._updateDOMProperties(null, props, transaction);
  var lazyTree = DOMLazyTree(el);
  this._createInitialChildren(transaction, props, context, lazyTree);
  mountImage = lazyTree;
} else {
  var tagOpen = this._createOpenTagMarkupAndPutListeners(transaction, props);
...
```

#### <a name="apidoc.element.react-dom.DOMPropertyOperations.setValueForAttribute"></a>[function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>setValueForAttribute (node, name, value)](#apidoc.element.react-dom.DOMPropertyOperations.setValueForAttribute)
- description and source-code
```javascript
setValueForAttribute = function (node, name, value) {
  if (!isAttributeNameSafe(name)) {
    return;
  }
  if (value == null) {
    node.removeAttribute(name);
  } else {
    node.setAttribute(name, '' + value);
  }

  if (process.env.NODE_ENV !== 'production') {
    var payload = {};
    payload[name] = value;
    ReactInstrumentation.debugTool.onHostOperation({
      instanceID: ReactDOMComponentTree.getInstanceFromNode(node)._debugID,
      type: 'update attribute',
      payload: payload
    });
  }
}
```
- example usage
```shell
...
    } else if (propertyInfo.hasBooleanValue || propertyInfo.hasOverloadedBooleanValue && value === true) {
      node.setAttribute(attributeName, '');
    } else {
      node.setAttribute(attributeName, '' + value);
    }
  }
} else if (DOMProperty.isCustomAttribute(name)) {
  DOMPropertyOperations.setValueForAttribute(node, name, value);
  return;
}

if (process.env.NODE_ENV !== 'production') {
  var payload = {};
  payload[name] = value;
  ReactInstrumentation.debugTool.onHostOperation({
...
```

#### <a name="apidoc.element.react-dom.DOMPropertyOperations.setValueForProperty"></a>[function <span class="apidocSignatureSpan">react-dom.DOMPropertyOperations.</span>setValueForProperty (node, name, value)](#apidoc.element.react-dom.DOMPropertyOperations.setValueForProperty)
- description and source-code
```javascript
setValueForProperty = function (node, name, value) {
  var propertyInfo = DOMProperty.properties.hasOwnProperty(name) ? DOMProperty.properties[name] : null;
  if (propertyInfo) {
    var mutationMethod = propertyInfo.mutationMethod;
    if (mutationMethod) {
      mutationMethod(node, value);
    } else if (shouldIgnoreValue(propertyInfo, value)) {
      this.deleteValueForProperty(node, name);
      return;
    } else if (propertyInfo.mustUseProperty) {
      // Contrary to 'setAttribute', object properties are properly
      // 'toString'ed by IE8/9.
      node[propertyInfo.propertyName] = value;
    } else {
      var attributeName = propertyInfo.attributeName;
      var namespace = propertyInfo.attributeNamespace;
      // 'setAttribute' with objects becomes only '[object]' in IE8/9,
      // ('' + value) makes it output the correct toString()-value.
      if (namespace) {
        node.setAttributeNS(namespace, attributeName, '' + value);
      } else if (propertyInfo.hasBooleanValue || propertyInfo.hasOverloadedBooleanValue && value === true) {
        node.setAttribute(attributeName, '');
      } else {
        node.setAttribute(attributeName, '' + value);
      }
    }
  } else if (DOMProperty.isCustomAttribute(name)) {
    DOMPropertyOperations.setValueForAttribute(node, name, value);
    return;
  }

  if (process.env.NODE_ENV !== 'production') {
    var payload = {};
    payload[name] = value;
    ReactInstrumentation.debugTool.onHostOperation({
      instanceID: ReactDOMComponentTree.getInstanceFromNode(node)._debugID,
      type: 'update attribute',
      payload: payload
    });
  }
}
```
- example usage
```shell
...
    }
  } else if (DOMProperty.properties[propKey] || DOMProperty.isCustomAttribute(propKey)) {
    var node = getNode(this);
    // If we're updating to null or undefined, we should remove the property
    // from the DOM node instead of inadvertently setting to a string. This
    // brings us in line with the same behavior we have on initial render.
    if (nextProp != null) {
      DOMPropertyOperations.setValueForProperty(node, propKey, nextProp);
    } else {
      DOMPropertyOperations.deleteValueForProperty(node, propKey);
    }
  }
}
if (styleUpdates) {
  CSSPropertyOperations.setValueForStyles(getNode(this), styleUpdates, this);
...
```



# <a name="apidoc.module.react-dom.Danger"></a>[module react-dom.Danger](#apidoc.module.react-dom.Danger)

#### <a name="apidoc.element.react-dom.Danger.dangerouslyReplaceNodeWithMarkup"></a>[function <span class="apidocSignatureSpan">react-dom.Danger.</span>dangerouslyReplaceNodeWithMarkup (oldChild, markup)](#apidoc.element.react-dom.Danger.dangerouslyReplaceNodeWithMarkup)
- description and source-code
```javascript
dangerouslyReplaceNodeWithMarkup = function (oldChild, markup) {
  !ExecutionEnvironment.canUseDOM ? process.env.NODE_ENV !== 'production' ? invariant(false, 'dangerouslyReplaceNodeWithMarkup(...):
Cannot render markup in a worker thread. Make sure 'window' and 'document' are available globally before requiring React when unit
 testing or use ReactDOMServer.renderToString() for server rendering.') : _prodInvariant('56') : void 0;
  !markup ? process.env.NODE_ENV !== 'production' ? invariant(false, 'dangerouslyReplaceNodeWithMarkup(...): Missing markup.') :
_prodInvariant('57') : void 0;
  !(oldChild.nodeName !== 'HTML') ? process.env.NODE_ENV !== 'production' ? invariant(false, 'dangerouslyReplaceNodeWithMarkup(...):
Cannot replace markup of the <html> node. This is because browser quirks make this unreliable and/or slow. If you want to render
 to the root you must use server rendering. See ReactDOMServer.renderToString().') : _prodInvariant('58') : void 0;

  if (typeof markup === 'string') {
    var newChild = createNodesFromMarkup(markup, emptyFunction)[0];
    oldChild.parentNode.replaceChild(newChild, oldChild);
  } else {
    DOMLazyTree.replaceChildWithTree(oldChild, markup);
  }
}
```
- example usage
```shell
...
  });
}
}

var dangerouslyReplaceNodeWithMarkup = Danger.dangerouslyReplaceNodeWithMarkup;
if (process.env.NODE_ENV !== 'production') {
dangerouslyReplaceNodeWithMarkup = function (oldChild, markup, prevInstance) {
  Danger.dangerouslyReplaceNodeWithMarkup(oldChild, markup);
  if (prevInstance._debugID !== 0) {
    ReactInstrumentation.debugTool.onHostOperation({
      instanceID: prevInstance._debugID,
      type: 'replace with',
      payload: markup.toString()
    });
  } else {
...
```



# <a name="apidoc.module.react-dom.EnterLeaveEventPlugin"></a>[module react-dom.EnterLeaveEventPlugin](#apidoc.module.react-dom.EnterLeaveEventPlugin)

#### <a name="apidoc.element.react-dom.EnterLeaveEventPlugin.extractEvents"></a>[function <span class="apidocSignatureSpan">react-dom.EnterLeaveEventPlugin.</span>extractEvents (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.EnterLeaveEventPlugin.extractEvents)
- description and source-code
```javascript
extractEvents = function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  if (topLevelType === 'topMouseOver' && (nativeEvent.relatedTarget || nativeEvent.fromElement)) {
    return null;
  }
  if (topLevelType !== 'topMouseOut' && topLevelType !== 'topMouseOver') {
    // Must not be a mouse in or mouse out - ignoring.
    return null;
  }

  var win;
  if (nativeEventTarget.window === nativeEventTarget) {
    // 'nativeEventTarget' is probably a window object.
    win = nativeEventTarget;
  } else {
    // TODO: Figure out why 'ownerDocument' is sometimes undefined in IE8.
    var doc = nativeEventTarget.ownerDocument;
    if (doc) {
      win = doc.defaultView || doc.parentWindow;
    } else {
      win = window;
    }
  }

  var from;
  var to;
  if (topLevelType === 'topMouseOut') {
    from = targetInst;
    var related = nativeEvent.relatedTarget || nativeEvent.toElement;
    to = related ? ReactDOMComponentTree.getClosestInstanceFromNode(related) : null;
  } else {
    // Moving to a node from outside the window.
    from = null;
    to = targetInst;
  }

  if (from === to) {
    // Nothing pertains to our managed components.
    return null;
  }

  var fromNode = from == null ? win : ReactDOMComponentTree.getNodeFromInstance(from);
  var toNode = to == null ? win : ReactDOMComponentTree.getNodeFromInstance(to);

  var leave = SyntheticMouseEvent.getPooled(eventTypes.mouseLeave, from, nativeEvent, nativeEventTarget);
  leave.type = 'mouseleave';
  leave.target = fromNode;
  leave.relatedTarget = toNode;

  var enter = SyntheticMouseEvent.getPooled(eventTypes.mouseEnter, to, nativeEvent, nativeEventTarget);
  enter.type = 'mouseenter';
  enter.target = toNode;
  enter.relatedTarget = fromNode;

  EventPropagators.accumulateEnterLeaveDispatches(leave, enter, from, to);

  return [leave, enter];
}
```
- example usage
```shell
...
extractEvents: function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  var events;
  var plugins = EventPluginRegistry.plugins;
  for (var i = 0; i < plugins.length; i++) {
    // Not every plugin in the ordering may be loaded at runtime.
    var possiblePlugin = plugins[i];
    if (possiblePlugin) {
      var extractedEvents = possiblePlugin.extractEvents(topLevelType, targetInst, nativeEvent, nativeEventTarget);
      if (extractedEvents) {
        events = accumulateInto(events, extractedEvents);
      }
    }
  }
  return events;
},
...
```



# <a name="apidoc.module.react-dom.EventPluginHub"></a>[module react-dom.EventPluginHub](#apidoc.module.react-dom.EventPluginHub)

#### <a name="apidoc.element.react-dom.EventPluginHub.__getListenerBank"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>__getListenerBank ()](#apidoc.element.react-dom.EventPluginHub.__getListenerBank)
- description and source-code
```javascript
__getListenerBank = function () {
  return listenerBank;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.EventPluginHub.__purge"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>__purge ()](#apidoc.element.react-dom.EventPluginHub.__purge)
- description and source-code
```javascript
__purge = function () {
  listenerBank = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.EventPluginHub.deleteAllListeners"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>deleteAllListeners (inst)](#apidoc.element.react-dom.EventPluginHub.deleteAllListeners)
- description and source-code
```javascript
deleteAllListeners = function (inst) {
  var key = getDictionaryKey(inst);
  for (var registrationName in listenerBank) {
    if (!listenerBank.hasOwnProperty(registrationName)) {
      continue;
    }

    if (!listenerBank[registrationName][key]) {
      continue;
    }

    var PluginModule = EventPluginRegistry.registrationNameModules[registrationName];
    if (PluginModule && PluginModule.willDeleteListener) {
      PluginModule.willDeleteListener(inst, registrationName);
    }

    delete listenerBank[registrationName][key];
  }
}
```
- example usage
```shell
...
     */
    !false ? process.env.NODE_ENV !== 'production' ? invariant(false, '<%s> tried to unmount. Because of cross-browser quirks it
 is impossible to unmount some top-level components (eg <html>, <head>, and <body>) reliably and efficiently. To fix this, have
a single top-level component that never unmounts render these elements.', this._tag) : _prodInvariant('66', this._tag) : void 0;
    break;
}

this.unmountChildren(safely);
ReactDOMComponentTree.uncacheNode(this);
EventPluginHub.deleteAllListeners(this);
this._rootNodeID = 0;
this._domID = 0;
this._wrapperState = null;

if (process.env.NODE_ENV !== 'production') {
  setAndValidateContentChildDev.call(this, null);
}
...
```

#### <a name="apidoc.element.react-dom.EventPluginHub.deleteListener"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>deleteListener (inst, registrationName)](#apidoc.element.react-dom.EventPluginHub.deleteListener)
- description and source-code
```javascript
deleteListener = function (inst, registrationName) {
  var PluginModule = EventPluginRegistry.registrationNameModules[registrationName];
  if (PluginModule && PluginModule.willDeleteListener) {
    PluginModule.willDeleteListener(inst, registrationName);
  }

  var bankForRegistrationName = listenerBank[registrationName];
  // TODO: This should never be null -- when is it?
  if (bankForRegistrationName) {
    var key = getDictionaryKey(inst);
    delete bankForRegistrationName[key];
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.EventPluginHub.enqueueEvents"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>enqueueEvents (events)](#apidoc.element.react-dom.EventPluginHub.enqueueEvents)
- description and source-code
```javascript
enqueueEvents = function (events) {
  if (events) {
    eventQueue = accumulateInto(eventQueue, events);
  }
}
```
- example usage
```shell
...
// components don't work properly in conjunction with event bubbling because
// the component is rerendered and the value reverted before all the event
// handlers can run. See https://github.com/facebook/react/issues/708.
ReactUpdates.batchedUpdates(runEventInBatch, event);
}

function runEventInBatch(event) {
EventPluginHub.enqueueEvents(event);
EventPluginHub.processEventQueue(false);
}

function startWatchingForChangeEventIE8(target, targetInst) {
activeElement = target;
activeElementInst = targetInst;
activeElement.attachEvent('onchange', manualDispatchChangeEvent);
...
```

#### <a name="apidoc.element.react-dom.EventPluginHub.extractEvents"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>extractEvents (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.EventPluginHub.extractEvents)
- description and source-code
```javascript
extractEvents = function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  var events;
  var plugins = EventPluginRegistry.plugins;
  for (var i = 0; i < plugins.length; i++) {
    // Not every plugin in the ordering may be loaded at runtime.
    var possiblePlugin = plugins[i];
    if (possiblePlugin) {
      var extractedEvents = possiblePlugin.extractEvents(topLevelType, targetInst, nativeEvent, nativeEventTarget);
      if (extractedEvents) {
        events = accumulateInto(events, extractedEvents);
      }
    }
  }
  return events;
}
```
- example usage
```shell
...
extractEvents: function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  var events;
  var plugins = EventPluginRegistry.plugins;
  for (var i = 0; i < plugins.length; i++) {
    // Not every plugin in the ordering may be loaded at runtime.
    var possiblePlugin = plugins[i];
    if (possiblePlugin) {
      var extractedEvents = possiblePlugin.extractEvents(topLevelType, targetInst, nativeEvent, nativeEventTarget);
      if (extractedEvents) {
        events = accumulateInto(events, extractedEvents);
      }
    }
  }
  return events;
},
...
```

#### <a name="apidoc.element.react-dom.EventPluginHub.getListener"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>getListener (inst, registrationName)](#apidoc.element.react-dom.EventPluginHub.getListener)
- description and source-code
```javascript
getListener = function (inst, registrationName) {
  // TODO: shouldPreventMouseEvent is DOM-specific and definitely should not
  // live here; needs to be moved to a better place soon
  var bankForRegistrationName = listenerBank[registrationName];
  if (shouldPreventMouseEvent(registrationName, inst._currentElement.type, inst._currentElement.props)) {
    return null;
  }
  var key = getDictionaryKey(inst);
  return bankForRegistrationName && bankForRegistrationName[key];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.EventPluginHub.processEventQueue"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>processEventQueue (simulated)](#apidoc.element.react-dom.EventPluginHub.processEventQueue)
- description and source-code
```javascript
processEventQueue = function (simulated) {
  // Set 'eventQueue' to null before processing it so that we can tell if more
  // events get enqueued while processing.
  var processingEventQueue = eventQueue;
  eventQueue = null;
  if (simulated) {
    forEachAccumulated(processingEventQueue, executeDispatchesAndReleaseSimulated);
  } else {
    forEachAccumulated(processingEventQueue, executeDispatchesAndReleaseTopLevel);
  }
  !!eventQueue ? process.env.NODE_ENV !== 'production' ? invariant(false, 'processEventQueue(): Additional events were enqueued
while processing an event queue. Support for this has not yet been implemented.') : _prodInvariant('95') : void 0;
  // This would be a good time to rethrow if any of the event handlers threw.
  ReactErrorUtils.rethrowCaughtError();
}
```
- example usage
```shell
...
  // the component is rerendered and the value reverted before all the event
  // handlers can run. See https://github.com/facebook/react/issues/708.
  ReactUpdates.batchedUpdates(runEventInBatch, event);
}

function runEventInBatch(event) {
  EventPluginHub.enqueueEvents(event);
  EventPluginHub.processEventQueue(false);
}

function startWatchingForChangeEventIE8(target, targetInst) {
  activeElement = target;
  activeElementInst = targetInst;
  activeElement.attachEvent('onchange', manualDispatchChangeEvent);
}
...
```

#### <a name="apidoc.element.react-dom.EventPluginHub.putListener"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginHub.</span>putListener (inst, registrationName, listener)](#apidoc.element.react-dom.EventPluginHub.putListener)
- description and source-code
```javascript
putListener = function (inst, registrationName, listener) {
  !(typeof listener === 'function') ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Expected %s listener to be a function
, instead got type %s', registrationName, typeof listener) : _prodInvariant('94', registrationName, typeof listener) : void 0;

  var key = getDictionaryKey(inst);
  var bankForRegistrationName = listenerBank[registrationName] || (listenerBank[registrationName] = {});
  bankForRegistrationName[key] = listener;

  var PluginModule = EventPluginRegistry.registrationNameModules[registrationName];
  if (PluginModule && PluginModule.didPutListener) {
    PluginModule.didPutListener(inst, registrationName, listener);
  }
}
```
- example usage
```shell
...
  return alreadyListeningTo[mountAt[topListenersIDKey]];
}

/**
 * 'ReactBrowserEventEmitter' is used to attach top-level event listeners. For
 * example:
 *
 *   EventPluginHub.putListener('myID', 'onClick', myFunction);
 *
 * This would allocate a "registration" of '('onClick', myFunction)' on 'myID'.
 *
 * @internal
 */
var ReactBrowserEventEmitter = _assign({}, ReactEventEmitterMixin, {
...
```



# <a name="apidoc.module.react-dom.EventPluginRegistry"></a>[module react-dom.EventPluginRegistry](#apidoc.module.react-dom.EventPluginRegistry)

#### <a name="apidoc.element.react-dom.EventPluginRegistry._resetEventPlugins"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginRegistry.</span>_resetEventPlugins ()](#apidoc.element.react-dom.EventPluginRegistry._resetEventPlugins)
- description and source-code
```javascript
_resetEventPlugins = function () {
  eventPluginOrder = null;
  for (var pluginName in namesToPlugins) {
    if (namesToPlugins.hasOwnProperty(pluginName)) {
      delete namesToPlugins[pluginName];
    }
  }
  EventPluginRegistry.plugins.length = 0;

  var eventNameDispatchConfigs = EventPluginRegistry.eventNameDispatchConfigs;
  for (var eventName in eventNameDispatchConfigs) {
    if (eventNameDispatchConfigs.hasOwnProperty(eventName)) {
      delete eventNameDispatchConfigs[eventName];
    }
  }

  var registrationNameModules = EventPluginRegistry.registrationNameModules;
  for (var registrationName in registrationNameModules) {
    if (registrationNameModules.hasOwnProperty(registrationName)) {
      delete registrationNameModules[registrationName];
    }
  }

  if (process.env.NODE_ENV !== 'production') {
    var possibleRegistrationNames = EventPluginRegistry.possibleRegistrationNames;
    for (var lowerCasedName in possibleRegistrationNames) {
      if (possibleRegistrationNames.hasOwnProperty(lowerCasedName)) {
        delete possibleRegistrationNames[lowerCasedName];
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.EventPluginRegistry.getPluginModuleForEvent"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginRegistry.</span>getPluginModuleForEvent (event)](#apidoc.element.react-dom.EventPluginRegistry.getPluginModuleForEvent)
- description and source-code
```javascript
getPluginModuleForEvent = function (event) {
  var dispatchConfig = event.dispatchConfig;
  if (dispatchConfig.registrationName) {
    return EventPluginRegistry.registrationNameModules[dispatchConfig.registrationName] || null;
  }
  if (dispatchConfig.phasedRegistrationNames !== undefined) {
    // pulling phasedRegistrationNames out of dispatchConfig helps Flow see
    // that it is not undefined.
    var phasedRegistrationNames = dispatchConfig.phasedRegistrationNames;

    for (var phase in phasedRegistrationNames) {
      if (!phasedRegistrationNames.hasOwnProperty(phase)) {
        continue;
      }
      var pluginModule = EventPluginRegistry.registrationNameModules[phasedRegistrationNames[phase]];
      if (pluginModule) {
        return pluginModule;
      }
    }
  }
  return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.EventPluginRegistry.injectEventPluginOrder"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginRegistry.</span>injectEventPluginOrder (injectedEventPluginOrder)](#apidoc.element.react-dom.EventPluginRegistry.injectEventPluginOrder)
- description and source-code
```javascript
injectEventPluginOrder = function (injectedEventPluginOrder) {
  !!eventPluginOrder ? process.env.NODE_ENV !== 'production' ? invariant(false, 'EventPluginRegistry: Cannot inject event plugin
 ordering more than once. You are likely trying to load more than one copy of React.') : _prodInvariant('101') : void 0;
  // Clone the ordering so it cannot be dynamically mutated.
  eventPluginOrder = Array.prototype.slice.call(injectedEventPluginOrder);
  recomputePluginOrdering();
}
```
- example usage
```shell
...
alreadyInjected = true;

ReactInjection.EventEmitter.injectReactEventListener(ReactEventListener);

/**
 * Inject modules for resolving DOM hierarchy and plugin ordering.
 */
ReactInjection.EventPluginHub.injectEventPluginOrder(DefaultEventPluginOrder);
ReactInjection.EventPluginUtils.injectComponentTree(ReactDOMComponentTree);
ReactInjection.EventPluginUtils.injectTreeTraversal(ReactDOMTreeTraversal);

/**
 * Some important event plugins included by default (without having to require
 * them).
 */
...
```

#### <a name="apidoc.element.react-dom.EventPluginRegistry.injectEventPluginsByName"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginRegistry.</span>injectEventPluginsByName (injectedNamesToPlugins)](#apidoc.element.react-dom.EventPluginRegistry.injectEventPluginsByName)
- description and source-code
```javascript
injectEventPluginsByName = function (injectedNamesToPlugins) {
  var isOrderingDirty = false;
  for (var pluginName in injectedNamesToPlugins) {
    if (!injectedNamesToPlugins.hasOwnProperty(pluginName)) {
      continue;
    }
    var pluginModule = injectedNamesToPlugins[pluginName];
    if (!namesToPlugins.hasOwnProperty(pluginName) || namesToPlugins[pluginName] !== pluginModule) {
      !!namesToPlugins[pluginName] ? process.env.NODE_ENV !== 'production' ? invariant(false, 'EventPluginRegistry: Cannot inject
 two different event plugins using the same name, '%s'.', pluginName) : _prodInvariant('102', pluginName) : void 0;
      namesToPlugins[pluginName] = pluginModule;
      isOrderingDirty = true;
    }
  }
  if (isOrderingDirty) {
    recomputePluginOrdering();
  }
}
```
- example usage
```shell
...
ReactInjection.EventPluginUtils.injectComponentTree(ReactDOMComponentTree);
ReactInjection.EventPluginUtils.injectTreeTraversal(ReactDOMTreeTraversal);

/**
 * Some important event plugins included by default (without having to require
 * them).
 */
ReactInjection.EventPluginHub.injectEventPluginsByName({
  SimpleEventPlugin: SimpleEventPlugin,
  EnterLeaveEventPlugin: EnterLeaveEventPlugin,
  ChangeEventPlugin: ChangeEventPlugin,
  SelectEventPlugin: SelectEventPlugin,
  BeforeInputEventPlugin: BeforeInputEventPlugin
});
...
```



# <a name="apidoc.module.react-dom.EventPluginUtils"></a>[module react-dom.EventPluginUtils](#apidoc.module.react-dom.EventPluginUtils)

#### <a name="apidoc.element.react-dom.EventPluginUtils.executeDirectDispatch"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>executeDirectDispatch (event)](#apidoc.element.react-dom.EventPluginUtils.executeDirectDispatch)
- description and source-code
```javascript
function executeDirectDispatch(event) {
  if (process.env.NODE_ENV !== 'production') {
    validateEventDispatches(event);
  }
  var dispatchListener = event._dispatchListeners;
  var dispatchInstance = event._dispatchInstances;
  !!Array.isArray(dispatchListener) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'executeDirectDispatch(...): Invalid
 'event'.') : _prodInvariant('103') : void 0;
  event.currentTarget = dispatchListener ? EventPluginUtils.getNodeFromInstance(dispatchInstance) : null;
  var res = dispatchListener ? dispatchListener(event) : null;
  event.currentTarget = null;
  event._dispatchListeners = null;
  event._dispatchInstances = null;
  return res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.EventPluginUtils.executeDispatchesInOrder"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>executeDispatchesInOrder (event, simulated)](#apidoc.element.react-dom.EventPluginUtils.executeDispatchesInOrder)
- description and source-code
```javascript
function executeDispatchesInOrder(event, simulated) {
  var dispatchListeners = event._dispatchListeners;
  var dispatchInstances = event._dispatchInstances;
  if (process.env.NODE_ENV !== 'production') {
    validateEventDispatches(event);
  }
  if (Array.isArray(dispatchListeners)) {
    for (var i = 0; i < dispatchListeners.length; i++) {
      if (event.isPropagationStopped()) {
        break;
      }
      // Listeners and Instances are two parallel arrays that are always in sync.
      executeDispatch(event, simulated, dispatchListeners[i], dispatchInstances[i]);
    }
  } else if (dispatchListeners) {
    executeDispatch(event, simulated, dispatchListeners, dispatchInstances);
  }
  event._dispatchListeners = null;
  event._dispatchInstances = null;
}
```
- example usage
```shell
...
 *
 * @param {?object} event Synthetic event to be dispatched.
 * @param {boolean} simulated If the event is simulated (changes exn behavior)
 * @private
 */
var executeDispatchesAndRelease = function (event, simulated) {
  if (event) {
    EventPluginUtils.executeDispatchesInOrder(event, simulated);

    if (!event.isPersistent()) {
      event.constructor.release(event);
    }
  }
};
var executeDispatchesAndReleaseSimulated = function (e) {
...
```

#### <a name="apidoc.element.react-dom.EventPluginUtils.executeDispatchesInOrderStopAtTrue"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>executeDispatchesInOrderStopAtTrue (event)](#apidoc.element.react-dom.EventPluginUtils.executeDispatchesInOrderStopAtTrue)
- description and source-code
```javascript
function executeDispatchesInOrderStopAtTrue(event) {
  var ret = executeDispatchesInOrderStopAtTrueImpl(event);
  event._dispatchInstances = null;
  event._dispatchListeners = null;
  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.EventPluginUtils.getInstanceFromNode"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>getInstanceFromNode (node)](#apidoc.element.react-dom.EventPluginUtils.getInstanceFromNode)
- description and source-code
```javascript
getInstanceFromNode = function (node) {
  return ComponentTree.getInstanceFromNode(node);
}
```
- example usage
```shell
...
    } else {
      removeDelimitedText(parentNode, openingComment, closingComment);
    }
  }

  if (process.env.NODE_ENV !== 'production') {
    ReactInstrumentation.debugTool.onHostOperation({
      instanceID: ReactDOMComponentTree.getInstanceFromNode(openingComment)._debugID,
      type: 'replace text',
      payload: stringText
    });
  }
}

var dangerouslyReplaceNodeWithMarkup = Danger.dangerouslyReplaceNodeWithMarkup;
...
```

#### <a name="apidoc.element.react-dom.EventPluginUtils.getLowestCommonAncestor"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>getLowestCommonAncestor (a, b)](#apidoc.element.react-dom.EventPluginUtils.getLowestCommonAncestor)
- description and source-code
```javascript
getLowestCommonAncestor = function (a, b) {
  return TreeTraversal.getLowestCommonAncestor(a, b);
}
```
- example usage
```shell
...
getNodeFromInstance: function (node) {
  return ComponentTree.getNodeFromInstance(node);
},
isAncestor: function (a, b) {
  return TreeTraversal.isAncestor(a, b);
},
getLowestCommonAncestor: function (a, b) {
  return TreeTraversal.getLowestCommonAncestor(a, b);
},
getParentInstance: function (inst) {
  return TreeTraversal.getParentInstance(inst);
},
traverseTwoPhase: function (target, fn, arg) {
  return TreeTraversal.traverseTwoPhase(target, fn, arg);
},
...
```

#### <a name="apidoc.element.react-dom.EventPluginUtils.getNodeFromInstance"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>getNodeFromInstance (node)](#apidoc.element.react-dom.EventPluginUtils.getNodeFromInstance)
- description and source-code
```javascript
getNodeFromInstance = function (node) {
  return ComponentTree.getNodeFromInstance(node);
}
```
- example usage
```shell
...

var ReactDOMComponentTree = require('./ReactDOMComponentTree');

var focusNode = require('fbjs/lib/focusNode');

var AutoFocusUtils = {
  focusDOMComponent: function () {
    focusNode(ReactDOMComponentTree.getNodeFromInstance(this));
  }
};

module.exports = AutoFocusUtils;
...
```

#### <a name="apidoc.element.react-dom.EventPluginUtils.getParentInstance"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>getParentInstance (inst)](#apidoc.element.react-dom.EventPluginUtils.getParentInstance)
- description and source-code
```javascript
getParentInstance = function (inst) {
  return TreeTraversal.getParentInstance(inst);
}
```
- example usage
```shell
...
isAncestor: function (a, b) {
  return TreeTraversal.isAncestor(a, b);
},
getLowestCommonAncestor: function (a, b) {
  return TreeTraversal.getLowestCommonAncestor(a, b);
},
getParentInstance: function (inst) {
  return TreeTraversal.getParentInstance(inst);
},
traverseTwoPhase: function (target, fn, arg) {
  return TreeTraversal.traverseTwoPhase(target, fn, arg);
},
traverseEnterLeave: function (from, to, fn, argFrom, argTo) {
  return TreeTraversal.traverseEnterLeave(from, to, fn, argFrom, argTo);
},
...
```

#### <a name="apidoc.element.react-dom.EventPluginUtils.hasDispatches"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>hasDispatches (event)](#apidoc.element.react-dom.EventPluginUtils.hasDispatches)
- description and source-code
```javascript
function hasDispatches(event) {
  return !!event._dispatchListeners;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.EventPluginUtils.isAncestor"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>isAncestor (a, b)](#apidoc.element.react-dom.EventPluginUtils.isAncestor)
- description and source-code
```javascript
isAncestor = function (a, b) {
  return TreeTraversal.isAncestor(a, b);
}
```
- example usage
```shell
...
getInstanceFromNode: function (node) {
  return ComponentTree.getInstanceFromNode(node);
},
getNodeFromInstance: function (node) {
  return ComponentTree.getNodeFromInstance(node);
},
isAncestor: function (a, b) {
  return TreeTraversal.isAncestor(a, b);
},
getLowestCommonAncestor: function (a, b) {
  return TreeTraversal.getLowestCommonAncestor(a, b);
},
getParentInstance: function (inst) {
  return TreeTraversal.getParentInstance(inst);
},
...
```

#### <a name="apidoc.element.react-dom.EventPluginUtils.isEndish"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>isEndish (topLevelType)](#apidoc.element.react-dom.EventPluginUtils.isEndish)
- description and source-code
```javascript
function isEndish(topLevelType) {
  return topLevelType === 'topMouseUp' || topLevelType === 'topTouchEnd' || topLevelType === 'topTouchCancel';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.EventPluginUtils.isMoveish"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>isMoveish (topLevelType)](#apidoc.element.react-dom.EventPluginUtils.isMoveish)
- description and source-code
```javascript
function isMoveish(topLevelType) {
  return topLevelType === 'topMouseMove' || topLevelType === 'topTouchMove';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.EventPluginUtils.isStartish"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>isStartish (topLevelType)](#apidoc.element.react-dom.EventPluginUtils.isStartish)
- description and source-code
```javascript
function isStartish(topLevelType) {
  return topLevelType === 'topMouseDown' || topLevelType === 'topTouchStart';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.EventPluginUtils.traverseEnterLeave"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>traverseEnterLeave (from, to, fn, argFrom, argTo)](#apidoc.element.react-dom.EventPluginUtils.traverseEnterLeave)
- description and source-code
```javascript
traverseEnterLeave = function (from, to, fn, argFrom, argTo) {
  return TreeTraversal.traverseEnterLeave(from, to, fn, argFrom, argTo);
}
```
- example usage
```shell
...
  getParentInstance: function (inst) {
    return TreeTraversal.getParentInstance(inst);
  },
  traverseTwoPhase: function (target, fn, arg) {
    return TreeTraversal.traverseTwoPhase(target, fn, arg);
  },
  traverseEnterLeave: function (from, to, fn, argFrom, argTo) {
    return TreeTraversal.traverseEnterLeave(from, to, fn, argFrom, argTo);
  },

  injection: injection
};

module.exports = EventPluginUtils;
...
```

#### <a name="apidoc.element.react-dom.EventPluginUtils.traverseTwoPhase"></a>[function <span class="apidocSignatureSpan">react-dom.EventPluginUtils.</span>traverseTwoPhase (target, fn, arg)](#apidoc.element.react-dom.EventPluginUtils.traverseTwoPhase)
- description and source-code
```javascript
traverseTwoPhase = function (target, fn, arg) {
  return TreeTraversal.traverseTwoPhase(target, fn, arg);
}
```
- example usage
```shell
...
  getLowestCommonAncestor: function (a, b) {
    return TreeTraversal.getLowestCommonAncestor(a, b);
  },
  getParentInstance: function (inst) {
    return TreeTraversal.getParentInstance(inst);
  },
  traverseTwoPhase: function (target, fn, arg) {
    return TreeTraversal.traverseTwoPhase(target, fn, arg);
  },
  traverseEnterLeave: function (from, to, fn, argFrom, argTo) {
    return TreeTraversal.traverseEnterLeave(from, to, fn, argFrom, argTo);
  },

  injection: injection
};
...
```



# <a name="apidoc.module.react-dom.EventPropagators"></a>[module react-dom.EventPropagators](#apidoc.module.react-dom.EventPropagators)

#### <a name="apidoc.element.react-dom.EventPropagators.accumulateDirectDispatches"></a>[function <span class="apidocSignatureSpan">react-dom.EventPropagators.</span>accumulateDirectDispatches (events)](#apidoc.element.react-dom.EventPropagators.accumulateDirectDispatches)
- description and source-code
```javascript
function accumulateDirectDispatches(events) {
  forEachAccumulated(events, accumulateDirectDispatchesSingle);
}
```
- example usage
```shell
...
  // sure it's marked and won't warn when setting additional properties.
  event.persist();
  _assign(event, eventData);

  if (dispatchConfig.phasedRegistrationNames) {
    EventPropagators.accumulateTwoPhaseDispatches(event);
  } else {
    EventPropagators.accumulateDirectDispatches(event);
  }

  ReactUpdates.batchedUpdates(function () {
    EventPluginHub.enqueueEvents(event);
    EventPluginHub.processEventQueue(true);
  });
};
...
```

#### <a name="apidoc.element.react-dom.EventPropagators.accumulateEnterLeaveDispatches"></a>[function <span class="apidocSignatureSpan">react-dom.EventPropagators.</span>accumulateEnterLeaveDispatches (leave, enter, from, to)](#apidoc.element.react-dom.EventPropagators.accumulateEnterLeaveDispatches)
- description and source-code
```javascript
function accumulateEnterLeaveDispatches(leave, enter, from, to) {
  EventPluginUtils.traverseEnterLeave(from, to, accumulateDispatches, leave, enter);
}
```
- example usage
```shell
...
    leave.relatedTarget = toNode;

    var enter = SyntheticMouseEvent.getPooled(eventTypes.mouseEnter, to, nativeEvent, nativeEventTarget);
    enter.type = 'mouseenter';
    enter.target = toNode;
    enter.relatedTarget = fromNode;

    EventPropagators.accumulateEnterLeaveDispatches(leave, enter, from, to);

    return [leave, enter];
  }

};

module.exports = EnterLeaveEventPlugin;
...
```

#### <a name="apidoc.element.react-dom.EventPropagators.accumulateTwoPhaseDispatches"></a>[function <span class="apidocSignatureSpan">react-dom.EventPropagators.</span>accumulateTwoPhaseDispatches (events)](#apidoc.element.react-dom.EventPropagators.accumulateTwoPhaseDispatches)
- description and source-code
```javascript
function accumulateTwoPhaseDispatches(events) {
  forEachAccumulated(events, accumulateTwoPhaseDispatchesSingle);
}
```
- example usage
```shell
...
 } else {
   var customData = getDataFromCustomEvent(nativeEvent);
   if (customData !== null) {
     event.data = customData;
   }
 }

 EventPropagators.accumulateTwoPhaseDispatches(event);
 return event;
}

/**
* @param {string} topLevelType Record from 'EventConstants'.
* @param {object} nativeEvent Native browser event.
* @return {?string} The string corresponding to this 'beforeInput' event.
...
```

#### <a name="apidoc.element.react-dom.EventPropagators.accumulateTwoPhaseDispatchesSkipTarget"></a>[function <span class="apidocSignatureSpan">react-dom.EventPropagators.</span>accumulateTwoPhaseDispatchesSkipTarget (events)](#apidoc.element.react-dom.EventPropagators.accumulateTwoPhaseDispatchesSkipTarget)
- description and source-code
```javascript
function accumulateTwoPhaseDispatchesSkipTarget(events) {
  forEachAccumulated(events, accumulateTwoPhaseDispatchesSingleSkipTarget);
}
```
- example usage
```shell
...
// (deepest ID) if it happens to be the current responder. The reasoning:
// It's strange to get an 'onMoveShouldSetResponder' when you're *already*
// the responder.
var skipOverBubbleShouldSetFrom = bubbleShouldSetFrom === responderInst;
var shouldSetEvent = ResponderSyntheticEvent.getPooled(shouldSetEventType, bubbleShouldSetFrom, nativeEvent, nativeEventTarget);
shouldSetEvent.touchHistory = ResponderTouchHistoryStore.touchHistory;
if (skipOverBubbleShouldSetFrom) {
  EventPropagators.accumulateTwoPhaseDispatchesSkipTarget(shouldSetEvent);
} else {
  EventPropagators.accumulateTwoPhaseDispatches(shouldSetEvent);
}
var wantsResponderInst = executeDispatchesInOrderStopAtTrue(shouldSetEvent);
if (!shouldSetEvent.isPersistent()) {
  shouldSetEvent.constructor.release(shouldSetEvent);
}
...
```



# <a name="apidoc.module.react-dom.FallbackCompositionState"></a>[module react-dom.FallbackCompositionState](#apidoc.module.react-dom.FallbackCompositionState)

#### <a name="apidoc.element.react-dom.FallbackCompositionState.FallbackCompositionState"></a>[function <span class="apidocSignatureSpan">react-dom.</span>FallbackCompositionState (root)](#apidoc.element.react-dom.FallbackCompositionState.FallbackCompositionState)
- description and source-code
```javascript
function FallbackCompositionState(root) {
  this._root = root;
  this._startText = this.getText();
  this._fallbackText = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.FallbackCompositionState.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.FallbackCompositionState.</span>getPooled (copyFieldsFrom)](#apidoc.element.react-dom.FallbackCompositionState.getPooled)
- description and source-code
```javascript
getPooled = function (copyFieldsFrom) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, copyFieldsFrom);
    return instance;
  } else {
    return new Klass(copyFieldsFrom);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.FallbackCompositionState.release"></a>[function <span class="apidocSignatureSpan">react-dom.FallbackCompositionState.</span>release (instance)](#apidoc.element.react-dom.FallbackCompositionState.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.FallbackCompositionState.prototype"></a>[module react-dom.FallbackCompositionState.prototype](#apidoc.module.react-dom.FallbackCompositionState.prototype)

#### <a name="apidoc.element.react-dom.FallbackCompositionState.prototype.destructor"></a>[function <span class="apidocSignatureSpan">react-dom.FallbackCompositionState.prototype.</span>destructor ()](#apidoc.element.react-dom.FallbackCompositionState.prototype.destructor)
- description and source-code
```javascript
destructor = function () {
  this._root = null;
  this._startText = null;
  this._fallbackText = null;
}
```
- example usage
```shell
...
    return new Klass(a1, a2, a3, a4);
  }
};

var standardReleaser = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
};

var DEFAULT_POOL_SIZE = 10;
var DEFAULT_POOLER = oneArgumentPooler;
...
```

#### <a name="apidoc.element.react-dom.FallbackCompositionState.prototype.getData"></a>[function <span class="apidocSignatureSpan">react-dom.FallbackCompositionState.prototype.</span>getData ()](#apidoc.element.react-dom.FallbackCompositionState.prototype.getData)
- description and source-code
```javascript
getData = function () {
  if (this._fallbackText) {
    return this._fallbackText;
  }

  var start;
  var startValue = this._startText;
  var startLength = startValue.length;
  var end;
  var endValue = this.getText();
  var endLength = endValue.length;

  for (start = 0; start < startLength; start++) {
    if (startValue[start] !== endValue[start]) {
      break;
    }
  }

  var minEnd = startLength - start;
  for (end = 1; end <= minEnd; end++) {
    if (startValue[startLength - end] !== endValue[endLength - end]) {
      break;
    }
  }

  var sliceTail = end > 1 ? 1 - end : undefined;
  this._fallbackText = endValue.slice(start, sliceTail);
  return this._fallbackText;
}
```
- example usage
```shell
...
if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}

var event = SyntheticCompositionEvent.getPooled(eventType, targetInst, nativeEvent, nativeEventTarget);

if (fallbackData) {
...
```

#### <a name="apidoc.element.react-dom.FallbackCompositionState.prototype.getText"></a>[function <span class="apidocSignatureSpan">react-dom.FallbackCompositionState.prototype.</span>getText ()](#apidoc.element.react-dom.FallbackCompositionState.prototype.getText)
- description and source-code
```javascript
getText = function () {
  if ('value' in this._root) {
    return this._root.value;
  }
  return this._root[getTextContentAccessor()];
}
```
- example usage
```shell
...
 * browser may natively replace the target node during composition, we can
 * use its position to find its replacement.
 *
 * @param {DOMEventTarget} root
 */
function FallbackCompositionState(root) {
this._root = root;
this._startText = this.getText();
this._fallbackText = null;
}

_assign(FallbackCompositionState.prototype, {
destructor: function () {
  this._root = null;
  this._startText = null;
...
```



# <a name="apidoc.module.react-dom.HTMLDOMPropertyConfig"></a>[module react-dom.HTMLDOMPropertyConfig](#apidoc.module.react-dom.HTMLDOMPropertyConfig)

#### <a name="apidoc.element.react-dom.HTMLDOMPropertyConfig.isCustomAttribute"></a>[function <span class="apidocSignatureSpan">react-dom.HTMLDOMPropertyConfig.</span>isCustomAttribute ()](#apidoc.element.react-dom.HTMLDOMPropertyConfig.isCustomAttribute)
- description and source-code
```javascript
isCustomAttribute = function () { [native code] }
```
- example usage
```shell
...
      return '';
    }
    var attributeName = propertyInfo.attributeName;
    if (propertyInfo.hasBooleanValue || propertyInfo.hasOverloadedBooleanValue && value === true) {
      return attributeName + '=""';
    }
    return attributeName + '=' + quoteAttributeValueForBrowser(value);
  } else if (DOMProperty.isCustomAttribute(name)) {
    if (value == null) {
      return '';
    }
    return name + '=' + quoteAttributeValueForBrowser(value);
  }
  return null;
},
...
```



# <a name="apidoc.module.react-dom.KeyEscapeUtils"></a>[module react-dom.KeyEscapeUtils](#apidoc.module.react-dom.KeyEscapeUtils)

#### <a name="apidoc.element.react-dom.KeyEscapeUtils.escape"></a>[function <span class="apidocSignatureSpan">react-dom.KeyEscapeUtils.</span>escape (key)](#apidoc.element.react-dom.KeyEscapeUtils.escape)
- description and source-code
```javascript
function escape(key) {
  var escapeRegex = /[=:]/g;
  var escaperLookup = {
    '=': '=0',
    ':': '=2'
  };
  var escapedString = ('' + key).replace(escapeRegex, function (match) {
    return escaperLookup[match];
  });

  return '$' + escapedString;
}
```
- example usage
```shell
...
* @return {string}
*/
function getComponentKey(component, index) {
 // Do some typechecking here since we call this blindly. We want to ensure
 // that we don't block potential future ES APIs.
 if (component && typeof component === 'object' && component.key != null) {
   // Explicit key
   return KeyEscapeUtils.escape(component.key);
 }
 // Implicit key determined by the index in the set
 return index.toString(36);
}

/**
* @param {?*} children Children tree container.
...
```

#### <a name="apidoc.element.react-dom.KeyEscapeUtils.unescape"></a>[function <span class="apidocSignatureSpan">react-dom.KeyEscapeUtils.</span>unescape (key)](#apidoc.element.react-dom.KeyEscapeUtils.unescape)
- description and source-code
```javascript
function unescape(key) {
  var unescapeRegex = /(=0|=2)/g;
  var unescaperLookup = {
    '=0': '=',
    '=2': ':'
  };
  var keySubstring = key[0] === '.' && key[1] === '$' ? key.substring(2) : key.substring(1);

  return ('' + keySubstring).replace(unescapeRegex, function (match) {
    return unescaperLookup[match];
  });
}
```
- example usage
```shell
...
  // We found a component instance.
  var keyUnique = childInstances[name] === undefined;
  if (process.env.NODE_ENV !== 'production') {
    if (!ReactComponentTreeHook) {
      ReactComponentTreeHook = require('react/lib/ReactComponentTreeHook');
    }
    if (!keyUnique) {
      process.env.NODE_ENV !== 'production' ? warning(false, 'flattenChildren(...): Encountered two children with the same key, ' + ''%
s'. Child keys must be unique; when two children share a key, only ' + 'the first child will be used.%s', KeyEscapeUtils.unescape
(name), ReactComponentTreeHook.getStackAddendumByID(selfDebugID)) : void 0;
    }
  }
  if (child != null && keyUnique) {
    childInstances[name] = instantiateReactComponent(child, true);
  }
}
...
```



# <a name="apidoc.module.react-dom.LinkedValueUtils"></a>[module react-dom.LinkedValueUtils](#apidoc.module.react-dom.LinkedValueUtils)

#### <a name="apidoc.element.react-dom.LinkedValueUtils.checkPropTypes"></a>[function <span class="apidocSignatureSpan">react-dom.LinkedValueUtils.</span>checkPropTypes (tagName, props, owner)](#apidoc.element.react-dom.LinkedValueUtils.checkPropTypes)
- description and source-code
```javascript
checkPropTypes = function (tagName, props, owner) {
  for (var propName in propTypes) {
    if (propTypes.hasOwnProperty(propName)) {
      var error = propTypes[propName](props, propName, tagName, 'prop', null, ReactPropTypesSecret);
    }
    if (error instanceof Error && !(error.message in loggedTypeFailures)) {
      // Only monitor this failure once because there tends to be a lot of the
      // same error.
      loggedTypeFailures[error.message] = true;

      var addendum = getDeclarationErrorAddendum(owner);
      process.env.NODE_ENV !== 'production' ? warning(false, 'Failed form propType: %s%s', error.message, addendum) : void 0;
    }
  }
}
```
- example usage
```shell
...
    });

    return hostProps;
  },

  mountWrapper: function (inst, props) {
    if (process.env.NODE_ENV !== 'production') {
LinkedValueUtils.checkPropTypes('input', props, inst._currentElement._owner);

var owner = inst._currentElement._owner;

if (props.valueLink !== undefined && !didWarnValueLink) {
  process.env.NODE_ENV !== 'production' ? warning(false, ''valueLink' prop on 'input' is deprecated; set 'value' and 'onChange'
instead.') : void 0;
  didWarnValueLink = true;
}
...
```

#### <a name="apidoc.element.react-dom.LinkedValueUtils.executeOnChange"></a>[function <span class="apidocSignatureSpan">react-dom.LinkedValueUtils.</span>executeOnChange (inputProps, event)](#apidoc.element.react-dom.LinkedValueUtils.executeOnChange)
- description and source-code
```javascript
executeOnChange = function (inputProps, event) {
  if (inputProps.valueLink) {
    _assertValueLink(inputProps);
    return inputProps.valueLink.requestChange(event.target.value);
  } else if (inputProps.checkedLink) {
    _assertCheckedLink(inputProps);
    return inputProps.checkedLink.requestChange(event.target.checked);
  } else if (inputProps.onChange) {
    return inputProps.onChange.call(undefined, event);
  }
}
```
- example usage
```shell
...
  }
}
};

function _handleChange(event) {
var props = this._currentElement.props;

var returnValue = LinkedValueUtils.executeOnChange(props, event);

// Here we use asap to wait until all updates have propagated, which
// is important when using controlled components within layers:
// https://github.com/facebook/react/issues/1698
ReactUpdates.asap(forceUpdateIfMounted, this);

var name = props.name;
...
```

#### <a name="apidoc.element.react-dom.LinkedValueUtils.getChecked"></a>[function <span class="apidocSignatureSpan">react-dom.LinkedValueUtils.</span>getChecked (inputProps)](#apidoc.element.react-dom.LinkedValueUtils.getChecked)
- description and source-code
```javascript
getChecked = function (inputProps) {
  if (inputProps.checkedLink) {
    _assertCheckedLink(inputProps);
    return inputProps.checkedLink.value;
  }
  return inputProps.checked;
}
```
- example usage
```shell
...
 * with an empty value (or 'defaultValue').
 *
 * @see http://www.w3.org/TR/2012/WD-html5-20121025/the-input-element.html
 */
var ReactDOMInput = {
  getHostProps: function (inst, props) {
var value = LinkedValueUtils.getValue(props);
var checked = LinkedValueUtils.getChecked(props);

var hostProps = _assign({
  // Make sure we set .type before any other properties (setting .value
  // before .type means .value is lost in IE11 and below)
  type: undefined,
  // Make sure we set .step before .value (setting .value before .step
  // means .value is rounded on mount, based upon step precision)
...
```

#### <a name="apidoc.element.react-dom.LinkedValueUtils.getValue"></a>[function <span class="apidocSignatureSpan">react-dom.LinkedValueUtils.</span>getValue (inputProps)](#apidoc.element.react-dom.LinkedValueUtils.getValue)
- description and source-code
```javascript
getValue = function (inputProps) {
  if (inputProps.valueLink) {
    _assertValueLink(inputProps);
    return inputProps.valueLink.value;
  }
  return inputProps.value;
}
```
- example usage
```shell
...
 * The rendered element will be initialized as unchecked (or 'defaultChecked')
 * with an empty value (or 'defaultValue').
 *
 * @see http://www.w3.org/TR/2012/WD-html5-20121025/the-input-element.html
 */
var ReactDOMInput = {
  getHostProps: function (inst, props) {
var value = LinkedValueUtils.getValue(props);
var checked = LinkedValueUtils.getChecked(props);

var hostProps = _assign({
  // Make sure we set .type before any other properties (setting .value
  // before .type means .value is lost in IE11 and below)
  type: undefined,
  // Make sure we set .step before .value (setting .value before .step
...
```



# <a name="apidoc.module.react-dom.PooledClass"></a>[module react-dom.PooledClass](#apidoc.module.react-dom.PooledClass)

#### <a name="apidoc.element.react-dom.PooledClass.addPoolingTo"></a>[function <span class="apidocSignatureSpan">react-dom.PooledClass.</span>addPoolingTo (CopyConstructor, pooler)](#apidoc.element.react-dom.PooledClass.addPoolingTo)
- description and source-code
```javascript
addPoolingTo = function (CopyConstructor, pooler) {
  // Casting as any so that flow ignores the actual implementation and trusts
  // it to match the type we declared
  var NewKlass = CopyConstructor;
  NewKlass.instancePool = [];
  NewKlass.getPooled = pooler || DEFAULT_POOLER;
  if (!NewKlass.poolSize) {
    NewKlass.poolSize = DEFAULT_POOL_SIZE;
  }
  NewKlass.release = standardReleaser;
  return NewKlass;
}
```
- example usage
```shell
...
  CallbackQueue.prototype.destructor = function destructor() {
    this.reset();
  };

  return CallbackQueue;
}();

module.exports = PooledClass.addPoolingTo(CallbackQueue);
...
```

#### <a name="apidoc.element.react-dom.PooledClass.fourArgumentPooler"></a>[function <span class="apidocSignatureSpan">react-dom.PooledClass.</span>fourArgumentPooler (a1, a2, a3, a4)](#apidoc.element.react-dom.PooledClass.fourArgumentPooler)
- description and source-code
```javascript
fourArgumentPooler = function (a1, a2, a3, a4) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2, a3, a4);
    return instance;
  } else {
    return new Klass(a1, a2, a3, a4);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.PooledClass.oneArgumentPooler"></a>[function <span class="apidocSignatureSpan">react-dom.PooledClass.</span>oneArgumentPooler (copyFieldsFrom)](#apidoc.element.react-dom.PooledClass.oneArgumentPooler)
- description and source-code
```javascript
oneArgumentPooler = function (copyFieldsFrom) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, copyFieldsFrom);
    return instance;
  } else {
    return new Klass(copyFieldsFrom);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.PooledClass.threeArgumentPooler"></a>[function <span class="apidocSignatureSpan">react-dom.PooledClass.</span>threeArgumentPooler (a1, a2, a3)](#apidoc.element.react-dom.PooledClass.threeArgumentPooler)
- description and source-code
```javascript
threeArgumentPooler = function (a1, a2, a3) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2, a3);
    return instance;
  } else {
    return new Klass(a1, a2, a3);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.PooledClass.twoArgumentPooler"></a>[function <span class="apidocSignatureSpan">react-dom.PooledClass.</span>twoArgumentPooler (a1, a2)](#apidoc.element.react-dom.PooledClass.twoArgumentPooler)
- description and source-code
```javascript
twoArgumentPooler = function (a1, a2) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2);
    return instance;
  } else {
    return new Klass(a1, a2);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactBrowserEventEmitter"></a>[module react-dom.ReactBrowserEventEmitter](#apidoc.module.react-dom.ReactBrowserEventEmitter)

#### <a name="apidoc.element.react-dom.ReactBrowserEventEmitter.ensureScrollValueMonitoring"></a>[function <span class="apidocSignatureSpan">react-dom.ReactBrowserEventEmitter.</span>ensureScrollValueMonitoring ()](#apidoc.element.react-dom.ReactBrowserEventEmitter.ensureScrollValueMonitoring)
- description and source-code
```javascript
ensureScrollValueMonitoring = function () {
  if (hasEventPageXY === undefined) {
    hasEventPageXY = ReactBrowserEventEmitter.supportsEventPageXY();
  }
  if (!hasEventPageXY && !isMonitoringScrollValue) {
    var refresh = ViewportMetrics.refreshScrollValues;
    ReactBrowserEventEmitter.ReactEventListener.monitorScrollValue(refresh);
    isMonitoringScrollValue = true;
  }
}
```
- example usage
```shell
...
// Various parts of our code (such as ReactCompositeComponent's
// _renderValidatedComponent) assume that calls to render aren't nested;
// verify that that's the case.
process.env.NODE_ENV !== 'production' ? warning(ReactCurrentOwner.current == null, '_renderNewRootComponent(): Render methods should
 be a pure function ' + 'of props and state; triggering nested component updates from ' + 'render is not allowed. If necessary,
trigger nested updates in ' + 'componentDidUpdate. Check the render method of %s.', ReactCurrentOwner.current && ReactCurrentOwner
.current.getName() || 'ReactCompositeComponent') : void 0;

!isValidContainer(container) ? process.env.NODE_ENV !== 'production' ? invariant(false, '_registerComponent(...): Target container
 is not a DOM element.') : _prodInvariant('37') : void 0;

ReactBrowserEventEmitter.ensureScrollValueMonitoring();
var componentInstance = instantiateReactComponent(nextElement, false);

// The initial render is synchronous but any updates that happen during
// rendering, in componentWillMount or componentDidMount, will be batched
// according to the current batching strategy.

ReactUpdates.batchedUpdates(batchedMountComponentIntoNode, componentInstance, container, shouldReuseMarkup, context);
...
```

#### <a name="apidoc.element.react-dom.ReactBrowserEventEmitter.handleTopLevel"></a>[function <span class="apidocSignatureSpan">react-dom.ReactBrowserEventEmitter.</span>handleTopLevel (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.ReactBrowserEventEmitter.handleTopLevel)
- description and source-code
```javascript
handleTopLevel = function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  var events = EventPluginHub.extractEvents(topLevelType, targetInst, nativeEvent, nativeEventTarget);
  runEventQueueInBatch(events);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactBrowserEventEmitter.isEnabled"></a>[function <span class="apidocSignatureSpan">react-dom.ReactBrowserEventEmitter.</span>isEnabled ()](#apidoc.element.react-dom.ReactBrowserEventEmitter.isEnabled)
- description and source-code
```javascript
isEnabled = function () {
  return !!(ReactBrowserEventEmitter.ReactEventListener && ReactBrowserEventEmitter.ReactEventListener.isEnabled());
}
```
- example usage
```shell
...
  }
},

/**
 * @return {boolean} True if callbacks are enabled.
 */
isEnabled: function () {
  return !!(ReactBrowserEventEmitter.ReactEventListener && ReactBrowserEventEmitter.ReactEventListener.isEnabled());
},

/**
 * We listen for bubbled touch events on the document object.
 *
 * Firefox v8.01 (and possibly others) exhibited strange behavior when
 * mounting 'onmousemove' events at some node that was not the document
...
```

#### <a name="apidoc.element.react-dom.ReactBrowserEventEmitter.listenTo"></a>[function <span class="apidocSignatureSpan">react-dom.ReactBrowserEventEmitter.</span>listenTo (registrationName, contentDocumentHandle)](#apidoc.element.react-dom.ReactBrowserEventEmitter.listenTo)
- description and source-code
```javascript
listenTo = function (registrationName, contentDocumentHandle) {
  var mountAt = contentDocumentHandle;
  var isListening = getListeningForDocument(mountAt);
  var dependencies = EventPluginRegistry.registrationNameDependencies[registrationName];

  for (var i = 0; i < dependencies.length; i++) {
    var dependency = dependencies[i];
    if (!(isListening.hasOwnProperty(dependency) && isListening[dependency])) {
      if (dependency === 'topWheel') {
        if (isEventSupported('wheel')) {
          ReactBrowserEventEmitter.ReactEventListener.trapBubbledEvent('topWheel', 'wheel', mountAt);
        } else if (isEventSupported('mousewheel')) {
          ReactBrowserEventEmitter.ReactEventListener.trapBubbledEvent('topWheel', 'mousewheel', mountAt);
        } else {
          // Firefox needs to capture a different mouse scroll event.
          // @see http://www.quirksmode.org/dom/events/tests/scroll.html
          ReactBrowserEventEmitter.ReactEventListener.trapBubbledEvent('topWheel', 'DOMMouseScroll', mountAt);
        }
      } else if (dependency === 'topScroll') {

        if (isEventSupported('scroll', true)) {
          ReactBrowserEventEmitter.ReactEventListener.trapCapturedEvent('topScroll', 'scroll', mountAt);
        } else {
          ReactBrowserEventEmitter.ReactEventListener.trapBubbledEvent('topScroll', 'scroll', ReactBrowserEventEmitter.ReactEventListener
.WINDOW_HANDLE);
        }
      } else if (dependency === 'topFocus' || dependency === 'topBlur') {

        if (isEventSupported('focus', true)) {
          ReactBrowserEventEmitter.ReactEventListener.trapCapturedEvent('topFocus', 'focus', mountAt);
          ReactBrowserEventEmitter.ReactEventListener.trapCapturedEvent('topBlur', 'blur', mountAt);
        } else if (isEventSupported('focusin')) {
          // IE has 'focusin' and 'focusout' events which bubble.
          // @see http://www.quirksmode.org/blog/archives/2008/04/delegating_the.html
          ReactBrowserEventEmitter.ReactEventListener.trapBubbledEvent('topFocus', 'focusin', mountAt);
          ReactBrowserEventEmitter.ReactEventListener.trapBubbledEvent('topBlur', 'focusout', mountAt);
        }

        // to make sure blur and focus event listeners are only attached once
        isListening.topBlur = true;
        isListening.topFocus = true;
      } else if (topEventMapping.hasOwnProperty(dependency)) {
        ReactBrowserEventEmitter.ReactEventListener.trapBubbledEvent(dependency, topEventMapping[dependency], mountAt);
      }

      isListening[dependency] = true;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactBrowserEventEmitter.setEnabled"></a>[function <span class="apidocSignatureSpan">react-dom.ReactBrowserEventEmitter.</span>setEnabled (enabled)](#apidoc.element.react-dom.ReactBrowserEventEmitter.setEnabled)
- description and source-code
```javascript
setEnabled = function (enabled) {
  if (ReactBrowserEventEmitter.ReactEventListener) {
    ReactBrowserEventEmitter.ReactEventListener.setEnabled(enabled);
  }
}
```
- example usage
```shell
...
/**
 * Sets whether or not any created callbacks should be enabled.
 *
 * @param {boolean} enabled True if callbacks should be enabled.
 */
setEnabled: function (enabled) {
  if (ReactBrowserEventEmitter.ReactEventListener) {
    ReactBrowserEventEmitter.ReactEventListener.setEnabled(enabled);
  }
},

/**
 * @return {boolean} True if callbacks are enabled.
 */
isEnabled: function () {
...
```

#### <a name="apidoc.element.react-dom.ReactBrowserEventEmitter.supportsEventPageXY"></a>[function <span class="apidocSignatureSpan">react-dom.ReactBrowserEventEmitter.</span>supportsEventPageXY ()](#apidoc.element.react-dom.ReactBrowserEventEmitter.supportsEventPageXY)
- description and source-code
```javascript
supportsEventPageXY = function () {
  if (!document.createEvent) {
    return false;
  }
  var ev = document.createEvent('MouseEvent');
  return ev != null && 'pageX' in ev;
}
```
- example usage
```shell
...
 *
 * NOTE: Scroll events do not bubble.
 *
 * @see http://www.quirksmode.org/dom/events/scroll.html
 */
ensureScrollValueMonitoring: function () {
  if (hasEventPageXY === undefined) {
    hasEventPageXY = ReactBrowserEventEmitter.supportsEventPageXY();
  }
  if (!hasEventPageXY && !isMonitoringScrollValue) {
    var refresh = ViewportMetrics.refreshScrollValues;
    ReactBrowserEventEmitter.ReactEventListener.monitorScrollValue(refresh);
    isMonitoringScrollValue = true;
  }
}
...
```

#### <a name="apidoc.element.react-dom.ReactBrowserEventEmitter.trapBubbledEvent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactBrowserEventEmitter.</span>trapBubbledEvent (topLevelType, handlerBaseName, handle)](#apidoc.element.react-dom.ReactBrowserEventEmitter.trapBubbledEvent)
- description and source-code
```javascript
trapBubbledEvent = function (topLevelType, handlerBaseName, handle) {
  return ReactBrowserEventEmitter.ReactEventListener.trapBubbledEvent(topLevelType, handlerBaseName, handle);
}
```
- example usage
```shell
...
var dependencies = EventPluginRegistry.registrationNameDependencies[registrationName];

for (var i = 0; i < dependencies.length; i++) {
  var dependency = dependencies[i];
  if (!(isListening.hasOwnProperty(dependency) && isListening[dependency])) {
    if (dependency === 'topWheel') {
      if (isEventSupported('wheel')) {
        ReactBrowserEventEmitter.ReactEventListener.trapBubbledEvent('topWheel', 'wheel', mountAt);
      } else if (isEventSupported('mousewheel')) {
        ReactBrowserEventEmitter.ReactEventListener.trapBubbledEvent('topWheel', 'mousewheel', mountAt);
      } else {
        // Firefox needs to capture a different mouse scroll event.
        // @see http://www.quirksmode.org/dom/events/tests/scroll.html
        ReactBrowserEventEmitter.ReactEventListener.trapBubbledEvent('topWheel', 'DOMMouseScroll', mountAt);
      }
...
```

#### <a name="apidoc.element.react-dom.ReactBrowserEventEmitter.trapCapturedEvent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactBrowserEventEmitter.</span>trapCapturedEvent (topLevelType, handlerBaseName, handle)](#apidoc.element.react-dom.ReactBrowserEventEmitter.trapCapturedEvent)
- description and source-code
```javascript
trapCapturedEvent = function (topLevelType, handlerBaseName, handle) {
  return ReactBrowserEventEmitter.ReactEventListener.trapCapturedEvent(topLevelType, handlerBaseName, handle);
}
```
- example usage
```shell
...
  // Firefox needs to capture a different mouse scroll event.
  // @see http://www.quirksmode.org/dom/events/tests/scroll.html
  ReactBrowserEventEmitter.ReactEventListener.trapBubbledEvent('topWheel', 'DOMMouseScroll', mountAt);
}
        } else if (dependency === 'topScroll') {

if (isEventSupported('scroll', true)) {
  ReactBrowserEventEmitter.ReactEventListener.trapCapturedEvent('topScroll', 'scroll', mountAt);
} else {
  ReactBrowserEventEmitter.ReactEventListener.trapBubbledEvent('topScroll', 'scroll', ReactBrowserEventEmitter.ReactEventListener
.WINDOW_HANDLE);
}
        } else if (dependency === 'topFocus' || dependency === 'topBlur') {

if (isEventSupported('focus', true)) {
  ReactBrowserEventEmitter.ReactEventListener.trapCapturedEvent('topFocus', 'focus', mountAt);
...
```



# <a name="apidoc.module.react-dom.ReactChildFiber"></a>[module react-dom.ReactChildFiber](#apidoc.module.react-dom.ReactChildFiber)

#### <a name="apidoc.element.react-dom.ReactChildFiber.cloneChildFibers"></a>[function <span class="apidocSignatureSpan">react-dom.ReactChildFiber.</span>cloneChildFibers (current, workInProgress)](#apidoc.element.react-dom.ReactChildFiber.cloneChildFibers)
- description and source-code
```javascript
cloneChildFibers = function (current, workInProgress) {
  if (!workInProgress.child) {
    return;
  }
  if (current && workInProgress.child === current.child) {
    // We use workInProgress.child since that lets Flow know that it can't be
    // null since we validated that already. However, as the line above suggests
    // they're actually the same thing.
    var currentChild = workInProgress.child;
    // TODO: This used to reset the pending priority. Not sure if that is needed.
    // workInProgress.pendingWorkPriority = current.pendingWorkPriority;
    // TODO: The below priority used to be set to NoWork which would've
    // dropped work. This is currently unobservable but will become
    // observable when the first sibling has lower priority work remaining
    // than the next sibling. At that point we should add tests that catches
    // this.
    var newChild = cloneFiber(currentChild, currentChild.pendingWorkPriority);
    workInProgress.child = newChild;
    cloneSiblings(currentChild, newChild, workInProgress);
  }

  // If there is no alternate, then we don't need to clone the children.
  // If the children of the alternate fiber is a different set, then we don't
  // need to clone. We need to reset the return fiber though since we'll
  // traverse down into them.
  var child = workInProgress.child;
  while (child) {
    child['return'] = workInProgress;
    child = child.sibling;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactChildFiber.reconcileChildFibers"></a>[function <span class="apidocSignatureSpan">react-dom.ReactChildFiber.</span>reconcileChildFibers (returnFiber, currentFirstChild, newChildren, priority)](#apidoc.element.react-dom.ReactChildFiber.reconcileChildFibers)
- description and source-code
```javascript
function reconcileChildFibers(returnFiber, currentFirstChild, newChildren, priority) {
  return createFirstChild(returnFiber, currentFirstChild, newChildren, priority);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactChildFiber.reconcileChildFibersInPlace"></a>[function <span class="apidocSignatureSpan">react-dom.ReactChildFiber.</span>reconcileChildFibersInPlace (returnFiber, currentFirstChild, newChildren, priority)](#apidoc.element.react-dom.ReactChildFiber.reconcileChildFibersInPlace)
- description and source-code
```javascript
function reconcileChildFibers(returnFiber, currentFirstChild, newChildren, priority) {
  return createFirstChild(returnFiber, currentFirstChild, newChildren, priority);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactChildReconciler"></a>[module react-dom.ReactChildReconciler](#apidoc.module.react-dom.ReactChildReconciler)

#### <a name="apidoc.element.react-dom.ReactChildReconciler.instantiateChildren"></a>[function <span class="apidocSignatureSpan">react-dom.ReactChildReconciler.</span>instantiateChildren (nestedChildNodes, transaction, context, selfDebugID // 0 in production and for roots )](#apidoc.element.react-dom.ReactChildReconciler.instantiateChildren)
- description and source-code
```javascript
instantiateChildren = function (nestedChildNodes, transaction, context, selfDebugID // 0 in production and for roots ) {
  if (nestedChildNodes == null) {
    return null;
  }
  var childInstances = {};

  if (process.env.NODE_ENV !== 'production') {
    traverseAllChildren(nestedChildNodes, function (childInsts, child, name) {
      return instantiateChild(childInsts, child, name, selfDebugID);
    }, childInstances);
  } else {
    traverseAllChildren(nestedChildNodes, instantiateChild, childInstances);
  }
  return childInstances;
}
```
- example usage
```shell
...

_reconcilerInstantiateChildren: function (nestedChildren, transaction, context) {
  if (process.env.NODE_ENV !== 'production') {
    var selfDebugID = getDebugID(this);
    if (this._currentElement) {
      try {
        ReactCurrentOwner.current = this._currentElement._owner;
        return ReactChildReconciler.instantiateChildren(nestedChildren, transaction, context, selfDebugID);
      } finally {
        ReactCurrentOwner.current = null;
      }
    }
  }
  return ReactChildReconciler.instantiateChildren(nestedChildren, transaction, context);
},
...
```

#### <a name="apidoc.element.react-dom.ReactChildReconciler.unmountChildren"></a>[function <span class="apidocSignatureSpan">react-dom.ReactChildReconciler.</span>unmountChildren (renderedChildren, safely)](#apidoc.element.react-dom.ReactChildReconciler.unmountChildren)
- description and source-code
```javascript
unmountChildren = function (renderedChildren, safely) {
  for (var name in renderedChildren) {
    if (renderedChildren.hasOwnProperty(name)) {
      var renderedChild = renderedChildren[name];
      ReactReconciler.unmountComponent(renderedChild, safely);
    }
  }
}
```
- example usage
```shell
...
     * take advantage of React's reconciliation for styling and <title>
     * management. So we just document it and throw in dangerous cases.
     */
    !false ? process.env.NODE_ENV !== 'production' ? invariant(false, '<%s> tried to unmount. Because of cross-browser quirks it
 is impossible to unmount some top-level components (eg <html>, <head>, and <body>) reliably and efficiently. To fix this, have
a single top-level component that never unmounts render these elements.', this._tag) : _prodInvariant('66', this._tag) : void 0;
    break;
}

this.unmountChildren(safely);
ReactDOMComponentTree.uncacheNode(this);
EventPluginHub.deleteAllListeners(this);
this._rootNodeID = 0;
this._domID = 0;
this._wrapperState = null;

if (process.env.NODE_ENV !== 'production') {
...
```

#### <a name="apidoc.element.react-dom.ReactChildReconciler.updateChildren"></a>[function <span class="apidocSignatureSpan">react-dom.ReactChildReconciler.</span>updateChildren (prevChildren, nextChildren, mountImages, removedNodes, transaction, hostParent, hostContainerInfo, context, selfDebugID // 0 in production and for roots )](#apidoc.element.react-dom.ReactChildReconciler.updateChildren)
- description and source-code
```javascript
updateChildren = function (prevChildren, nextChildren, mountImages, removedNodes, transaction, hostParent, hostContainerInfo, context, selfDebugID // 0 in production and for roots ) {
  // We currently don't have a way to track moves here but if we use iterators
  // instead of for..in we can zip the iterators and check if an item has
  // moved.
  // TODO: If nothing has changed, return the prevChildren object so that we
  // can quickly bailout if nothing has changed.
  if (!nextChildren && !prevChildren) {
    return;
  }
  var name;
  var prevChild;
  for (name in nextChildren) {
    if (!nextChildren.hasOwnProperty(name)) {
      continue;
    }
    prevChild = prevChildren && prevChildren[name];
    var prevElement = prevChild && prevChild._currentElement;
    var nextElement = nextChildren[name];
    if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
      ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
      nextChildren[name] = prevChild;
    } else {
      if (prevChild) {
        removedNodes[name] = ReactReconciler.getHostNode(prevChild);
        ReactReconciler.unmountComponent(prevChild, false);
      }
      // The child must be instantiated before it's mounted.
      var nextChildInstance = instantiateReactComponent(nextElement, true);
      nextChildren[name] = nextChildInstance;
      // Creating mount image now ensures refs are resolved in right order
      // (see https://github.com/facebook/react/pull/7101 for explanation).
      var nextChildMountImage = ReactReconciler.mountComponent(nextChildInstance, transaction, hostParent, hostContainerInfo, context
, selfDebugID);
      mountImages.push(nextChildMountImage);
    }
  }
  // Unmount children that are no longer present.
  for (name in prevChildren) {
    if (prevChildren.hasOwnProperty(name) && !(nextChildren && nextChildren.hasOwnProperty(name))) {
      prevChild = prevChildren[name];
      removedNodes[name] = ReactReconciler.getHostNode(prevChild);
      ReactReconciler.unmountComponent(prevChild, false);
    }
  }
}
```
- example usage
```shell
...
var nextChildren = nextContent != null ? null : nextProps.children;

// If we're switching from children to content/html or vice versa, remove
// the old content
var lastHasContentOrHtml = lastContent != null || lastHtml != null;
var nextHasContentOrHtml = nextContent != null || nextHtml != null;
if (lastChildren != null && nextChildren == null) {
  this.updateChildren(null, transaction, context);
} else if (lastHasContentOrHtml && !nextHasContentOrHtml) {
  this.updateTextContent('');
  if (process.env.NODE_ENV !== 'production') {
    ReactInstrumentation.debugTool.onSetChildren(this._debugID, []);
  }
}
...
```



# <a name="apidoc.module.react-dom.ReactComponentBrowserEnvironment"></a>[module react-dom.ReactComponentBrowserEnvironment](#apidoc.module.react-dom.ReactComponentBrowserEnvironment)

#### <a name="apidoc.element.react-dom.ReactComponentBrowserEnvironment.processChildrenUpdates"></a>[function <span class="apidocSignatureSpan">react-dom.ReactComponentBrowserEnvironment.</span>processChildrenUpdates (parentInst, updates)](#apidoc.element.react-dom.ReactComponentBrowserEnvironment.processChildrenUpdates)
- description and source-code
```javascript
processChildrenUpdates = function (parentInst, updates) {
  var node = ReactDOMComponentTree.getNodeFromInstance(parentInst);
  DOMChildrenOperations.processUpdates(node, updates);
}
```
- example usage
```shell
...

/**
 * Processes any enqueued updates.
 *
 * @private
 */
function processQueue(inst, updateQueue) {
ReactComponentEnvironment.processChildrenUpdates(inst, updateQueue);
}

var setChildrenForInstrumentation = emptyFunction;
if (process.env.NODE_ENV !== 'production') {
var getDebugID = function (inst) {
  if (!inst._debugID) {
    // Check for ART-like instances. TODO: This is silly/gross.
...
```

#### <a name="apidoc.element.react-dom.ReactComponentBrowserEnvironment.replaceNodeWithMarkup"></a>[function <span class="apidocSignatureSpan">react-dom.ReactComponentBrowserEnvironment.</span>replaceNodeWithMarkup (oldChild, markup, prevInstance)](#apidoc.element.react-dom.ReactComponentBrowserEnvironment.replaceNodeWithMarkup)
- description and source-code
```javascript
replaceNodeWithMarkup = function (oldChild, markup, prevInstance) {
  Danger.dangerouslyReplaceNodeWithMarkup(oldChild, markup);
  if (prevInstance._debugID !== 0) {
    ReactInstrumentation.debugTool.onHostOperation({
      instanceID: prevInstance._debugID,
      type: 'replace with',
      payload: markup.toString()
    });
  } else {
    var nextInstance = ReactDOMComponentTree.getInstanceFromNode(markup.node);
    if (nextInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onHostOperation({
        instanceID: nextInstance._debugID,
        type: 'mount',
        payload: markup.toString()
      });
    }
  }
}
```
- example usage
```shell
...

/**
 * Overridden in shallow rendering.
 *
 * @protected
 */
_replaceNodeWithMarkup: function (oldHostNode, nextMarkup, prevInstance) {
  ReactComponentEnvironment.replaceNodeWithMarkup(oldHostNode, nextMarkup, prevInstance);
},

/**
 * @protected
 */
_renderValidatedComponentWithoutOwnerOrContext: function () {
  var inst = this._instance;
...
```



# <a name="apidoc.module.react-dom.ReactComponentEnvironment"></a>[module react-dom.ReactComponentEnvironment](#apidoc.module.react-dom.ReactComponentEnvironment)

#### <a name="apidoc.element.react-dom.ReactComponentEnvironment.processChildrenUpdates"></a>[function <span class="apidocSignatureSpan">react-dom.ReactComponentEnvironment.</span>processChildrenUpdates (parentInst, updates)](#apidoc.element.react-dom.ReactComponentEnvironment.processChildrenUpdates)
- description and source-code
```javascript
processChildrenUpdates = function (parentInst, updates) {
  var node = ReactDOMComponentTree.getNodeFromInstance(parentInst);
  DOMChildrenOperations.processUpdates(node, updates);
}
```
- example usage
```shell
...

/**
 * Processes any enqueued updates.
 *
 * @private
 */
function processQueue(inst, updateQueue) {
ReactComponentEnvironment.processChildrenUpdates(inst, updateQueue);
}

var setChildrenForInstrumentation = emptyFunction;
if (process.env.NODE_ENV !== 'production') {
var getDebugID = function (inst) {
  if (!inst._debugID) {
    // Check for ART-like instances. TODO: This is silly/gross.
...
```

#### <a name="apidoc.element.react-dom.ReactComponentEnvironment.replaceNodeWithMarkup"></a>[function <span class="apidocSignatureSpan">react-dom.ReactComponentEnvironment.</span>replaceNodeWithMarkup (oldChild, markup, prevInstance)](#apidoc.element.react-dom.ReactComponentEnvironment.replaceNodeWithMarkup)
- description and source-code
```javascript
replaceNodeWithMarkup = function (oldChild, markup, prevInstance) {
  Danger.dangerouslyReplaceNodeWithMarkup(oldChild, markup);
  if (prevInstance._debugID !== 0) {
    ReactInstrumentation.debugTool.onHostOperation({
      instanceID: prevInstance._debugID,
      type: 'replace with',
      payload: markup.toString()
    });
  } else {
    var nextInstance = ReactDOMComponentTree.getInstanceFromNode(markup.node);
    if (nextInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onHostOperation({
        instanceID: nextInstance._debugID,
        type: 'mount',
        payload: markup.toString()
      });
    }
  }
}
```
- example usage
```shell
...

/**
 * Overridden in shallow rendering.
 *
 * @protected
 */
_replaceNodeWithMarkup: function (oldHostNode, nextMarkup, prevInstance) {
  ReactComponentEnvironment.replaceNodeWithMarkup(oldHostNode, nextMarkup, prevInstance);
},

/**
 * @protected
 */
_renderValidatedComponentWithoutOwnerOrContext: function () {
  var inst = this._instance;
...
```



# <a name="apidoc.module.react-dom.ReactComponentTreeTestUtils"></a>[module react-dom.ReactComponentTreeTestUtils](#apidoc.module.react-dom.ReactComponentTreeTestUtils)

#### <a name="apidoc.element.react-dom.ReactComponentTreeTestUtils.expectTree"></a>[function <span class="apidocSignatureSpan">react-dom.ReactComponentTreeTestUtils.</span>expectTree (rootID, expectedTree, parentPath)](#apidoc.element.react-dom.ReactComponentTreeTestUtils.expectTree)
- description and source-code
```javascript
function expectTree(rootID, expectedTree, parentPath) {
  var displayName = ReactComponentTreeHook.getDisplayName(rootID);
  var ownerID = ReactComponentTreeHook.getOwnerID(rootID);
  var parentID = ReactComponentTreeHook.getParentID(rootID);
  var childIDs = ReactComponentTreeHook.getChildIDs(rootID);
  var text = ReactComponentTreeHook.getText(rootID);
  var element = ReactComponentTreeHook.getElement(rootID);
  var path = parentPath ? parentPath + ' > ' + displayName : displayName;

  function expectEqual(actual, expected, name) {
    // Get Jasmine to print descriptive error messages.
    // We pass path so that we know where the mismatch occurred.
    expect(_defineProperty({
      path: path
    }, name, actual)).toEqual(_defineProperty({
      path: path
    }, name, expected));
  }

  if (expectedTree.parentDisplayName !== undefined) {
    expectEqual(ReactComponentTreeHook.getDisplayName(parentID), expectedTree.parentDisplayName, 'parentDisplayName');
  }
  if (expectedTree.ownerDisplayName !== undefined) {
    expectEqual(ReactComponentTreeHook.getDisplayName(ownerID), expectedTree.ownerDisplayName, 'ownerDisplayName');
  }
  if (expectedTree.parentID !== undefined) {
    expectEqual(parentID, expectedTree.parentID, 'parentID');
  }
  if (expectedTree.text !== undefined) {
    expectEqual(text, expectedTree.text, 'text');
    expectEqual('' + element, expectedTree.text, 'element.toString()');
  } else {
    expectEqual(text, null, 'text');
  }
  if (expectedTree.element !== undefined) {
    // TODO: Comparing elements makes tests run out of memory on errors.
    // For now, compare just types.
    expectEqual(element && element.type, expectedTree.element && expectedTree.element.type, 'element.type');
  } else if (text == null) {
    expectEqual(typeof element, 'object', 'typeof element');
  }
  if (expectedTree.children !== undefined) {
    expectEqual(childIDs.length, expectedTree.children.length, 'children.length');
    for (var i = 0; i < childIDs.length; i++) {
      expectTree(childIDs[i], _extends({ parentID: rootID }, expectedTree.children[i]), path);
    }
  } else {
    expectEqual(childIDs, [], 'childIDs');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactComponentTreeTestUtils.getRegisteredDisplayNames"></a>[function <span class="apidocSignatureSpan">react-dom.ReactComponentTreeTestUtils.</span>getRegisteredDisplayNames ()](#apidoc.element.react-dom.ReactComponentTreeTestUtils.getRegisteredDisplayNames)
- description and source-code
```javascript
function getRegisteredDisplayNames() {
  return ReactComponentTreeHook.getRegisteredIDs().map(ReactComponentTreeHook.getDisplayName);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactComponentTreeTestUtils.getRootDisplayNames"></a>[function <span class="apidocSignatureSpan">react-dom.ReactComponentTreeTestUtils.</span>getRootDisplayNames ()](#apidoc.element.react-dom.ReactComponentTreeTestUtils.getRootDisplayNames)
- description and source-code
```javascript
function getRootDisplayNames() {
  return ReactComponentTreeHook.getRootIDs().map(ReactComponentTreeHook.getDisplayName);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactCompositeComponent"></a>[module react-dom.ReactCompositeComponent](#apidoc.module.react-dom.ReactCompositeComponent)

#### <a name="apidoc.element.react-dom.ReactCompositeComponent._checkContextTypes"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_checkContextTypes (typeSpecs, values, location)](#apidoc.element.react-dom.ReactCompositeComponent._checkContextTypes)
- description and source-code
```javascript
_checkContextTypes = function (typeSpecs, values, location) {
  if (process.env.NODE_ENV !== 'production') {
    checkReactTypeSpec(typeSpecs, values, location, this.getName(), null, this._debugID);
  }
}
```
- example usage
```shell
...
 * @private
 */
_processContext: function (context) {
  var maskedContext = this._maskContext(context);
  if (process.env.NODE_ENV !== 'production') {
    var Component = this._currentElement.type;
    if (Component.contextTypes) {
      this._checkContextTypes(Component.contextTypes, maskedContext, 'context');
    }
  }
  return maskedContext;
},

/**
 * @param {object} currentContext
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent._constructComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_constructComponent (doConstruct, publicProps, publicContext, updateQueue)](#apidoc.element.react-dom.ReactCompositeComponent._constructComponent)
- description and source-code
```javascript
_constructComponent = function (doConstruct, publicProps, publicContext, updateQueue) {
  if (process.env.NODE_ENV !== 'production') {
    ReactCurrentOwner.current = this;
    try {
      return this._constructComponentWithoutOwner(doConstruct, publicProps, publicContext, updateQueue);
    } finally {
      ReactCurrentOwner.current = null;
    }
  } else {
    return this._constructComponentWithoutOwner(doConstruct, publicProps, publicContext, updateQueue);
  }
}
```
- example usage
```shell
...

var Component = this._currentElement.type;

var updateQueue = transaction.getUpdateQueue();

// Initialize the public class
var doConstruct = shouldConstruct(Component);
var inst = this._constructComponent(doConstruct, publicProps, publicContext, updateQueue);
var renderedElement;

// Support functional components
if (!doConstruct && (inst == null || inst.render == null)) {
  renderedElement = inst;
  warnIfInvalidElement(Component, renderedElement);
  !(inst === null || inst === false || React.isValidElement(inst)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s(...): A valid React element (or null) must be returned. You may have returned undefined, an array or some other invalid object
.', Component.displayName || Component.name || 'Component') : _prodInvariant('105', Component.displayName || Component.name || '
Component') : void 0;
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent._constructComponentWithoutOwner"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_constructComponentWithoutOwner (doConstruct, publicProps, publicContext, updateQueue)](#apidoc.element.react-dom.ReactCompositeComponent._constructComponentWithoutOwner)
- description and source-code
```javascript
_constructComponentWithoutOwner = function (doConstruct, publicProps, publicContext, updateQueue) {
  var Component = this._currentElement.type;

  if (doConstruct) {
    if (process.env.NODE_ENV !== 'production') {
      return measureLifeCyclePerf(function () {
        return new Component(publicProps, publicContext, updateQueue);
      }, this._debugID, 'ctor');
    } else {
      return new Component(publicProps, publicContext, updateQueue);
    }
  }

  // This can still be an instance in case of factory components
  // but we'll count this as time spent rendering as the more common case.
  if (process.env.NODE_ENV !== 'production') {
    return measureLifeCyclePerf(function () {
      return Component(publicProps, publicContext, updateQueue);
    }, this._debugID, 'render');
  } else {
    return Component(publicProps, publicContext, updateQueue);
  }
}
```
- example usage
```shell
...
  return markup;
},

_constructComponent: function (doConstruct, publicProps, publicContext, updateQueue) {
  if (process.env.NODE_ENV !== 'production') {
    ReactCurrentOwner.current = this;
    try {
      return this._constructComponentWithoutOwner(doConstruct, publicProps, publicContext, updateQueue);
    } finally {
      ReactCurrentOwner.current = null;
    }
  } else {
    return this._constructComponentWithoutOwner(doConstruct, publicProps, publicContext, updateQueue);
  }
},
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent._maskContext"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_maskContext (context)](#apidoc.element.react-dom.ReactCompositeComponent._maskContext)
- description and source-code
```javascript
_maskContext = function (context) {
  var Component = this._currentElement.type;
  var contextTypes = Component.contextTypes;
  if (!contextTypes) {
    return emptyObject;
  }
  var maskedContext = {};
  for (var contextName in contextTypes) {
    maskedContext[contextName] = context[contextName];
  }
  return maskedContext;
}
```
- example usage
```shell
...
 * 'contextTypes', and asserts that they are valid.
 *
 * @param {object} context
 * @return {?object}
 * @private
 */
_processContext: function (context) {
  var maskedContext = this._maskContext(context);
  if (process.env.NODE_ENV !== 'production') {
    var Component = this._currentElement.type;
    if (Component.contextTypes) {
      this._checkContextTypes(Component.contextTypes, maskedContext, 'context');
    }
  }
  return maskedContext;
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent._performComponentUpdate"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_performComponentUpdate (nextElement, nextProps, nextState, nextContext, transaction, unmaskedContext)](#apidoc.element.react-dom.ReactCompositeComponent._performComponentUpdate)
- description and source-code
```javascript
_performComponentUpdate = function (nextElement, nextProps, nextState, nextContext, transaction, unmaskedContext) {
  var _this2 = this;

  var inst = this._instance;

  var hasComponentDidUpdate = Boolean(inst.componentDidUpdate);
  var prevProps;
  var prevState;
  var prevContext;
  if (hasComponentDidUpdate) {
    prevProps = inst.props;
    prevState = inst.state;
    prevContext = inst.context;
  }

  if (inst.componentWillUpdate) {
    if (process.env.NODE_ENV !== 'production') {
      measureLifeCyclePerf(function () {
        return inst.componentWillUpdate(nextProps, nextState, nextContext);
      }, this._debugID, 'componentWillUpdate');
    } else {
      inst.componentWillUpdate(nextProps, nextState, nextContext);
    }
  }

  this._currentElement = nextElement;
  this._context = unmaskedContext;
  inst.props = nextProps;
  inst.state = nextState;
  inst.context = nextContext;

  this._updateRenderedComponent(transaction, unmaskedContext);

  if (hasComponentDidUpdate) {
    if (process.env.NODE_ENV !== 'production') {
      transaction.getReactMountReady().enqueue(function () {
        measureLifeCyclePerf(inst.componentDidUpdate.bind(inst, prevProps, prevState, prevContext), _this2._debugID, 'componentDidUpdate
');
      });
    } else {
      transaction.getReactMountReady().enqueue(inst.componentDidUpdate.bind(inst, prevProps, prevState, prevContext), inst);
    }
  }
}
```
- example usage
```shell
...
  process.env.NODE_ENV !== 'production' ? warning(shouldUpdate !== undefined, '%s.shouldComponentUpdate(): Returned undefined instead
 of a ' + 'boolean value. Make sure to return true or false.', this.getName() || 'ReactCompositeComponent') : void 0;
}

this._updateBatchNumber = null;
if (shouldUpdate) {
  this._pendingForceUpdate = false;
  // Will set 'this.props', 'this.state' and 'this.context'.
  this._performComponentUpdate(nextParentElement, nextProps, nextState, nextContext, transaction, nextUnmaskedContext);
} else {
  // If it's determined that a component should not update, we still want
  // to set props and state but we shortcut the rest of the update.
  this._currentElement = nextParentElement;
  this._context = nextUnmaskedContext;
  inst.props = nextProps;
  inst.state = nextState;
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent._processChildContext"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_processChildContext (currentContext)](#apidoc.element.react-dom.ReactCompositeComponent._processChildContext)
- description and source-code
```javascript
_processChildContext = function (currentContext) {
  var Component = this._currentElement.type;
  var inst = this._instance;
  var childContext;

  if (inst.getChildContext) {
    if (process.env.NODE_ENV !== 'production') {
      ReactInstrumentation.debugTool.onBeginProcessingChildContext();
      try {
        childContext = inst.getChildContext();
      } finally {
        ReactInstrumentation.debugTool.onEndProcessingChildContext();
      }
    } else {
      childContext = inst.getChildContext();
    }
  }

  if (childContext) {
    !(typeof Component.childContextTypes === 'object') ? process.env.NODE_ENV !== 'production' ? invariant(false, '%s.getChildContext
(): childContextTypes must be defined in order to use getChildContext().', this.getName() || 'ReactCompositeComponent') : _prodInvariant
('107', this.getName() || 'ReactCompositeComponent') : void 0;
    if (process.env.NODE_ENV !== 'production') {
      this._checkContextTypes(Component.childContextTypes, childContext, 'child context');
    }
    for (var name in childContext) {
      !(name in Component.childContextTypes) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%s.getChildContext(): key
 "%s" is not defined in childContextTypes.', this.getName() || 'ReactCompositeComponent', name) : _prodInvariant('108', this.getName
() || 'ReactCompositeComponent', name) : void 0;
    }
    return _assign({}, currentContext, childContext);
  }
  return currentContext;
}
```
- example usage
```shell
...

var nodeType = ReactNodeTypes.getType(renderedElement);
this._renderedNodeType = nodeType;
var child = this._instantiateReactComponent(renderedElement, nodeType !== ReactNodeTypes.EMPTY /* shouldHaveDebugID */
);
this._renderedComponent = child;

var markup = ReactReconciler.mountComponent(child, transaction, hostParent, hostContainerInfo, this._processChildContext(context
), debugID);

if (process.env.NODE_ENV !== 'production') {
  if (debugID !== 0) {
    var childDebugIDs = child._debugID !== 0 ? [child._debugID] : [];
    ReactInstrumentation.debugTool.onSetChildren(debugID, childDebugIDs);
  }
}
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent._processContext"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_processContext (context)](#apidoc.element.react-dom.ReactCompositeComponent._processContext)
- description and source-code
```javascript
_processContext = function (context) {
  var maskedContext = this._maskContext(context);
  if (process.env.NODE_ENV !== 'production') {
    var Component = this._currentElement.type;
    if (Component.contextTypes) {
      this._checkContextTypes(Component.contextTypes, maskedContext, 'context');
    }
  }
  return maskedContext;
}
```
- example usage
```shell
...

this._context = context;
this._mountOrder = nextMountID++;
this._hostParent = hostParent;
this._hostContainerInfo = hostContainerInfo;

var publicProps = this._currentElement.props;
var publicContext = this._processContext(context);

var Component = this._currentElement.type;

var updateQueue = transaction.getUpdateQueue();

// Initialize the public class
var doConstruct = shouldConstruct(Component);
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent._processPendingState"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_processPendingState (props, context)](#apidoc.element.react-dom.ReactCompositeComponent._processPendingState)
- description and source-code
```javascript
_processPendingState = function (props, context) {
  var inst = this._instance;
  var queue = this._pendingStateQueue;
  var replace = this._pendingReplaceState;
  this._pendingReplaceState = false;
  this._pendingStateQueue = null;

  if (!queue) {
    return inst.state;
  }

  if (replace && queue.length === 1) {
    return queue[0];
  }

  var nextState = _assign({}, replace ? queue[0] : inst.state);
  for (var i = replace ? 1 : 0; i < queue.length; i++) {
    var partial = queue[i];
    _assign(nextState, typeof partial === 'function' ? partial.call(inst, nextState, props, context) : partial);
  }

  return nextState;
}
```
- example usage
```shell
...
    try {
markup = this.performInitialMount(renderedElement, hostParent, hostContainerInfo, transaction, context);
    } catch (e) {
// Roll back to checkpoint, handle error (which may add items to the transaction), and take a new checkpoint
transaction.rollback(checkpoint);
this._instance.unstable_handleError(e);
if (this._pendingStateQueue) {
  this._instance.state = this._processPendingState(this._instance.props, this._instance.context);
}
checkpoint = transaction.checkpoint();

this._renderedComponent.unmountComponent(true);
transaction.rollback(checkpoint);

// Try again - we've informed the component about the error, so they can render an error message this time.
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent._renderValidatedComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_renderValidatedComponent ()](#apidoc.element.react-dom.ReactCompositeComponent._renderValidatedComponent)
- description and source-code
```javascript
_renderValidatedComponent = function () {
  var renderedElement;
  if (process.env.NODE_ENV !== 'production' || this._compositeType !== CompositeTypes.StatelessFunctional) {
    ReactCurrentOwner.current = this;
    try {
      renderedElement = this._renderValidatedComponentWithoutOwnerOrContext();
    } finally {
      ReactCurrentOwner.current = null;
    }
  } else {
    renderedElement = this._renderValidatedComponentWithoutOwnerOrContext();
  }
  !(
  // TODO: An 'isValidNode' function would probably be more appropriate
  renderedElement === null || renderedElement === false || React.isValidElement(renderedElement)) ? process.env.NODE_ENV !== 'production
' ? invariant(false, '%s.render(): A valid React element (or null) must be returned. You may have returned undefined, an array or
 some other invalid object.', this.getName() || 'ReactCompositeComponent') : _prodInvariant('109', this.getName() || 'ReactCompositeComponent
') : void 0;

  return renderedElement;
}
```
- example usage
```shell
...
  if (this._pendingStateQueue) {
    inst.state = this._processPendingState(inst.props, inst.context);
  }
}

// If not a stateless component, we now render
if (renderedElement === undefined) {
  renderedElement = this._renderValidatedComponent();
}

var nodeType = ReactNodeTypes.getType(renderedElement);
this._renderedNodeType = nodeType;
var child = this._instantiateReactComponent(renderedElement, nodeType !== ReactNodeTypes.EMPTY /* shouldHaveDebugID */
);
this._renderedComponent = child;
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent._renderValidatedComponentWithoutOwnerOrContext"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_renderValidatedComponentWithoutOwnerOrContext ()](#apidoc.element.react-dom.ReactCompositeComponent._renderValidatedComponentWithoutOwnerOrContext)
- description and source-code
```javascript
_renderValidatedComponentWithoutOwnerOrContext = function () {
  var inst = this._instance;
  var renderedElement;

  if (process.env.NODE_ENV !== 'production') {
    renderedElement = measureLifeCyclePerf(function () {
      return inst.render();
    }, this._debugID, 'render');
  } else {
    renderedElement = inst.render();
  }

  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (renderedElement === undefined && inst.render._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      renderedElement = null;
    }
  }

  return renderedElement;
}
```
- example usage
```shell
...
 * @private
 */
_renderValidatedComponent: function () {
  var renderedElement;
  if (process.env.NODE_ENV !== 'production' || this._compositeType !== CompositeTypes.StatelessFunctional) {
    ReactCurrentOwner.current = this;
    try {
      renderedElement = this._renderValidatedComponentWithoutOwnerOrContext();
    } finally {
      ReactCurrentOwner.current = null;
    }
  } else {
    renderedElement = this._renderValidatedComponentWithoutOwnerOrContext();
  }
  !(
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent._replaceNodeWithMarkup"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_replaceNodeWithMarkup (oldHostNode, nextMarkup, prevInstance)](#apidoc.element.react-dom.ReactCompositeComponent._replaceNodeWithMarkup)
- description and source-code
```javascript
_replaceNodeWithMarkup = function (oldHostNode, nextMarkup, prevInstance) {
  ReactComponentEnvironment.replaceNodeWithMarkup(oldHostNode, nextMarkup, prevInstance);
}
```
- example usage
```shell
...
    if (process.env.NODE_ENV !== 'production') {
      if (debugID !== 0) {
        var childDebugIDs = child._debugID !== 0 ? [child._debugID] : [];
        ReactInstrumentation.debugTool.onSetChildren(debugID, childDebugIDs);
      }
    }

    this._replaceNodeWithMarkup(oldHostNode, nextMarkup, prevComponentInstance);
  }
},

/**
 * Overridden in shallow rendering.
 *
 * @protected
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent._updateRenderedComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>_updateRenderedComponent (transaction, context)](#apidoc.element.react-dom.ReactCompositeComponent._updateRenderedComponent)
- description and source-code
```javascript
_updateRenderedComponent = function (transaction, context) {
  var prevComponentInstance = this._renderedComponent;
  var prevRenderedElement = prevComponentInstance._currentElement;
  var nextRenderedElement = this._renderValidatedComponent();

  var debugID = 0;
  if (process.env.NODE_ENV !== 'production') {
    debugID = this._debugID;
  }

  if (shouldUpdateReactComponent(prevRenderedElement, nextRenderedElement)) {
    ReactReconciler.receiveComponent(prevComponentInstance, nextRenderedElement, transaction, this._processChildContext(context));
  } else {
    var oldHostNode = ReactReconciler.getHostNode(prevComponentInstance);
    ReactReconciler.unmountComponent(prevComponentInstance, false);

    var nodeType = ReactNodeTypes.getType(nextRenderedElement);
    this._renderedNodeType = nodeType;
    var child = this._instantiateReactComponent(nextRenderedElement, nodeType !== ReactNodeTypes.EMPTY<span class="apidocCodeCommentSpan"> /* shouldHaveDebugID */
</span>    );
    this._renderedComponent = child;

    var nextMarkup = ReactReconciler.mountComponent(child, transaction, this._hostParent, this._hostContainerInfo, this._processChildContext
(context), debugID);

    if (process.env.NODE_ENV !== 'production') {
      if (debugID !== 0) {
        var childDebugIDs = child._debugID !== 0 ? [child._debugID] : [];
        ReactInstrumentation.debugTool.onSetChildren(debugID, childDebugIDs);
      }
    }

    this._replaceNodeWithMarkup(oldHostNode, nextMarkup, prevComponentInstance);
  }
}
```
- example usage
```shell
...

this._currentElement = nextElement;
this._context = unmaskedContext;
inst.props = nextProps;
inst.state = nextState;
inst.context = nextContext;

this._updateRenderedComponent(transaction, unmaskedContext);

if (hasComponentDidUpdate) {
  if (process.env.NODE_ENV !== 'production') {
    transaction.getReactMountReady().enqueue(function () {
      measureLifeCyclePerf(inst.componentDidUpdate.bind(inst, prevProps, prevState, prevContext), _this2._debugID, 'componentDidUpdate
');
    });
  } else {
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent.attachRef"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>attachRef (ref, component)](#apidoc.element.react-dom.ReactCompositeComponent.attachRef)
- description and source-code
```javascript
attachRef = function (ref, component) {
  var inst = this.getPublicInstance();
  !(inst != null) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Stateless function components cannot have refs.') :
_prodInvariant('110') : void 0;
  var publicComponentInstance = component.getPublicInstance();
  if (process.env.NODE_ENV !== 'production') {
    var componentName = component && component.getName ? component.getName() : 'a component';
    process.env.NODE_ENV !== 'production' ? warning(publicComponentInstance != null || component._compositeType !== CompositeTypes
.StatelessFunctional, 'Stateless function components cannot be given refs ' + '(See ref "%s" in %s created by %s). ' + 'Attempts
 to access this ref will fail.', ref, componentName, this.getName()) : void 0;
  }
  var refs = inst.refs === emptyObject ? inst.refs = {} : inst.refs;
  refs[ref] = publicComponentInstance;
}
```
- example usage
```shell
...
 * @param {string} ref Name by which to refer to the component.
 * @param {ReactOwner} owner Component on which to record the ref.
 * @final
 * @internal
 */
addComponentAsRefTo: function (component, ref, owner) {
  !isValidOwner(owner) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'addComponentAsRefTo(...): Only a ReactOwner can
 have refs. You might be adding a ref to a component that was not created inside a component\'s 'render' method, or you have multiple copies of React loaded (details: https://fb.me/react-refs-must-have-owner).') : _prodInvariant('119') : void 0;
  owner.attachRef(ref, component);
},

/**
 * Removes a component by ref from an owner component.
 *
 * @param {ReactComponent} component Component to dereference.
 * @param {string} ref Name of the ref to remove.
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent.construct"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>construct (element)](#apidoc.element.react-dom.ReactCompositeComponent.construct)
- description and source-code
```javascript
construct = function (element) {
  this._currentElement = element;
  this._rootNodeID = 0;
  this._compositeType = null;
  this._instance = null;
  this._hostParent = null;
  this._hostContainerInfo = null;

  // See ReactUpdateQueue
  this._updateBatchNumber = null;
  this._pendingElement = null;
  this._pendingStateQueue = null;
  this._pendingReplaceState = false;
  this._pendingForceUpdate = false;

  this._renderedNodeType = null;
  this._renderedComponent = null;
  this._context = null;
  this._mountOrder = 0;
  this._topLevelWrapper = null;

  // See ReactUpdates and ReactUpdateQueue.
  this._pendingCallbacks = null;

  // ComponentWillUnmount shall only be called once
  this._calledComponentWillUnmount = false;

  if (process.env.NODE_ENV !== 'production') {
    this._warnedAboutRefsInRender = false;
  }
}
```
- example usage
```shell
...

var ShallowComponentWrapper = function (element) {
// TODO: Consolidate with instantiateReactComponent
if (process.env.NODE_ENV !== 'production') {
  this._debugID = getNextDebugID();
}

this.construct(element);
};
_assign(ShallowComponentWrapper.prototype, ReactCompositeComponent, {
_constructComponent: ReactCompositeComponent._constructComponentWithoutOwner,
_instantiateReactComponent: function (element) {
  return new NoopInternalComponent(element);
},
_replaceNodeWithMarkup: function () {},
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent.detachRef"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>detachRef (ref)](#apidoc.element.react-dom.ReactCompositeComponent.detachRef)
- description and source-code
```javascript
detachRef = function (ref) {
  var refs = this.getPublicInstance().refs;
  delete refs[ref];
}
```
- example usage
```shell
...
   */
  removeComponentAsRefFrom: function (component, ref, owner) {
    !isValidOwner(owner) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'removeComponentAsRefFrom(...): Only a ReactOwner
 can have refs. You might be removing a ref to a component that was not created inside a component\'s 'render' method, or you have multiple copies of React loaded (details: https://fb.me/react-refs-must-have-owner).') : _prodInvariant('120') : void 0;
    var ownerPublicInstance = owner.getPublicInstance();
    // Check that 'component''s owner is still alive and that 'component' is still the current ref
    // because we do not want to detach the ref if another component stole it.
    if (ownerPublicInstance && ownerPublicInstance.refs[ref] === component.getPublicInstance()) {
      owner.detachRef(ref);
    }
  }

};

module.exports = ReactOwner;
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent.getHostNode"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>getHostNode ()](#apidoc.element.react-dom.ReactCompositeComponent.getHostNode)
- description and source-code
```javascript
getHostNode = function () {
  return ReactReconciler.getHostNode(this._renderedComponent);
}
```
- example usage
```shell
...
var prevElement = prevChild && prevChild._currentElement;
var nextElement = nextChildren[name];
if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
  ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
  nextChildren[name] = prevChild;
} else {
  if (prevChild) {
    removedNodes[name] = ReactReconciler.getHostNode(prevChild);
    ReactReconciler.unmountComponent(prevChild, false);
  }
  // The child must be instantiated before it's mounted.
  var nextChildInstance = instantiateReactComponent(nextElement, true);
  nextChildren[name] = nextChildInstance;
  // Creating mount image now ensures refs are resolved in right order
  // (see https://github.com/facebook/react/pull/7101 for explanation).
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent.getName"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>getName ()](#apidoc.element.react-dom.ReactCompositeComponent.getName)
- description and source-code
```javascript
getName = function () {
  var type = this._currentElement.type;
  var constructor = this._instance && this._instance.constructor;
  return type.displayName || constructor && constructor.displayName || type.name || constructor && constructor.name || null;
}
```
- example usage
```shell
...

  warnedForNaNValue = true;
  process.env.NODE_ENV !== 'production' ? warning(false, ''NaN' is an invalid value for the '%s' css style property.%s', name, checkRenderMessage
(owner)) : void 0;
};

var checkRenderMessage = function (owner) {
  if (owner) {
    var name = owner.getName();
    if (name) {
      return ' Check the render method of '' + name + ''.';
    }
  }
  return '';
};
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent.getPublicInstance"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>getPublicInstance ()](#apidoc.element.react-dom.ReactCompositeComponent.getPublicInstance)
- description and source-code
```javascript
getPublicInstance = function () {
  var inst = this._instance;
  if (this._compositeType === CompositeTypes.StatelessFunctional) {
    return null;
  }
  return inst;
}
```
- example usage
```shell
...
 *
 * @param {string} ref Reference name.
 * @param {component} component Component to store as 'ref'.
 * @final
 * @private
 */
attachRef: function (ref, component) {
  var inst = this.getPublicInstance();
  !(inst != null) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Stateless function components cannot have refs.') :
_prodInvariant('110') : void 0;
  var publicComponentInstance = component.getPublicInstance();
  if (process.env.NODE_ENV !== 'production') {
    var componentName = component && component.getName ? component.getName() : 'a component';
    process.env.NODE_ENV !== 'production' ? warning(publicComponentInstance != null || component._compositeType !== CompositeTypes
.StatelessFunctional, 'Stateless function components cannot be given refs ' + '(See ref "%s" in %s created by %s). ' + 'Attempts
 to access this ref will fail.', ref, componentName, this.getName()) : void 0;
  }
  var refs = inst.refs === emptyObject ? inst.refs = {} : inst.refs;
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent.mountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>mountComponent (transaction, hostParent, hostContainerInfo, context)](#apidoc.element.react-dom.ReactCompositeComponent.mountComponent)
- description and source-code
```javascript
mountComponent = function (transaction, hostParent, hostContainerInfo, context) {
  var _this = this;

  this._context = context;
  this._mountOrder = nextMountID++;
  this._hostParent = hostParent;
  this._hostContainerInfo = hostContainerInfo;

  var publicProps = this._currentElement.props;
  var publicContext = this._processContext(context);

  var Component = this._currentElement.type;

  var updateQueue = transaction.getUpdateQueue();

  // Initialize the public class
  var doConstruct = shouldConstruct(Component);
  var inst = this._constructComponent(doConstruct, publicProps, publicContext, updateQueue);
  var renderedElement;

  // Support functional components
  if (!doConstruct && (inst == null || inst.render == null)) {
    renderedElement = inst;
    warnIfInvalidElement(Component, renderedElement);
    !(inst === null || inst === false || React.isValidElement(inst)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s(...): A valid React element (or null) must be returned. You may have returned undefined, an array or some other invalid object
.', Component.displayName || Component.name || 'Component') : _prodInvariant('105', Component.displayName || Component.name || '
Component') : void 0;
    inst = new StatelessComponent(Component);
    this._compositeType = CompositeTypes.StatelessFunctional;
  } else {
    if (isPureComponent(Component)) {
      this._compositeType = CompositeTypes.PureClass;
    } else {
      this._compositeType = CompositeTypes.ImpureClass;
    }
  }

  if (process.env.NODE_ENV !== 'production') {
    // This will throw later in _renderValidatedComponent, but add an early
    // warning now to help debugging
    if (inst.render == null) {
      process.env.NODE_ENV !== 'production' ? warning(false, '%s(...): No 'render' method found on the returned component ' + 'instance
: you may have forgotten to define 'render'.', Component.displayName || Component.name || 'Component') : void 0;
    }

    var propsMutated = inst.props !== publicProps;
    var componentName = Component.displayName || Component.name || 'Component';

    process.env.NODE_ENV !== 'production' ? warning(inst.props === undefined || !propsMutated, '%s(...): When calling super() in
 '%s', make sure to pass ' + 'up the same props that your component\'s constructor was passed.', componentName, componentName) : void 0;
  }

  // These should be set up in the constructor, but as a convenience for
  // simpler class abstractions, we set them up after the fact.
  inst.props = publicProps;
  inst.context = publicContext;
  inst.refs = emptyObject;
  inst.updater = updateQueue;

  this._instance = inst;

  // Store a reference from the instance back to the internal representation
  ReactInstanceMap.set(inst, this);

  if (process.env.NODE_ENV !== 'production') {
    // Since plain JS classes are defined without any special initialization
    // logic, we can not catch common errors early. Therefore, we have to
    // catch them here, at initialization time, instead.
    process.env.NODE_ENV !== 'production' ? warning(!inst.getInitialState || inst.getInitialState.isReactClassApproved || inst.state
, 'getInitialState was defined on %s, a plain JavaScript class. ' + 'This is only supported for classes created using React.createClass
. ' + 'Did you mean to define a state property instead?', this.getName() || 'a component') : void 0;
    process.env.NODE_ENV !== 'production' ? warning(!inst.getDefaultProps || inst.getDefaultProps.isReactClassApproved, 'getDefaultProps
 was defined on %s, a plain JavaScript class. ' + 'This is only supported for classes created using React.createClass. ' + 'Use
a static property to define defaultProps instead.', this.getName() || 'a component') : void 0;
    process.env.NODE_ENV !== 'production' ? warning(!inst.propTypes, 'propTypes was defined as an instance property on %s. Use a
 static ' + 'property to define propTypes instead.', this.getName() || 'a component') : void 0;
    process.env.NODE_ENV !== 'production' ? warning(!inst.contextTypes, 'contextTypes was defined as an instance property on %s.
U ...
```
- example usage
```shell
...
      ReactReconciler.unmountComponent(prevChild, false);
    }
    // The child must be instantiated before it's mounted.
    var nextChildInstance = instantiateReactComponent(nextElement, true);
    nextChildren[name] = nextChildInstance;
    // Creating mount image now ensures refs are resolved in right order
    // (see https://github.com/facebook/react/pull/7101 for explanation).
    var nextChildMountImage = ReactReconciler.mountComponent(nextChildInstance, transaction, hostParent, hostContainerInfo, context
, selfDebugID);
    mountImages.push(nextChildMountImage);
  }
}
// Unmount children that are no longer present.
for (name in prevChildren) {
  if (prevChildren.hasOwnProperty(name) && !(nextChildren && nextChildren.hasOwnProperty(name))) {
    prevChild = prevChildren[name];
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent.performInitialMount"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>performInitialMount (renderedElement, hostParent, hostContainerInfo, transaction, context)](#apidoc.element.react-dom.ReactCompositeComponent.performInitialMount)
- description and source-code
```javascript
performInitialMount = function (renderedElement, hostParent, hostContainerInfo, transaction, context) {
  var inst = this._instance;

  var debugID = 0;
  if (process.env.NODE_ENV !== 'production') {
    debugID = this._debugID;
  }

  if (inst.componentWillMount) {
    if (process.env.NODE_ENV !== 'production') {
      measureLifeCyclePerf(function () {
        return inst.componentWillMount();
      }, debugID, 'componentWillMount');
    } else {
      inst.componentWillMount();
    }
    // When mounting, calls to 'setState' by 'componentWillMount' will set
    // 'this._pendingStateQueue' without triggering a re-render.
    if (this._pendingStateQueue) {
      inst.state = this._processPendingState(inst.props, inst.context);
    }
  }

  // If not a stateless component, we now render
  if (renderedElement === undefined) {
    renderedElement = this._renderValidatedComponent();
  }

  var nodeType = ReactNodeTypes.getType(renderedElement);
  this._renderedNodeType = nodeType;
  var child = this._instantiateReactComponent(renderedElement, nodeType !== ReactNodeTypes.EMPTY<span class="apidocCodeCommentSpan"> /* shouldHaveDebugID */
</span>  );
  this._renderedComponent = child;

  var markup = ReactReconciler.mountComponent(child, transaction, hostParent, hostContainerInfo, this._processChildContext(context
), debugID);

  if (process.env.NODE_ENV !== 'production') {
    if (debugID !== 0) {
      var childDebugIDs = child._debugID !== 0 ? [child._debugID] : [];
      ReactInstrumentation.debugTool.onSetChildren(debugID, childDebugIDs);
    }
  }

  return markup;
}
```
- example usage
```shell
...
this._pendingReplaceState = false;
this._pendingForceUpdate = false;

var markup;
if (inst.unstable_handleError) {
  markup = this.performInitialMountWithErrorHandling(renderedElement, hostParent, hostContainerInfo, transaction, context);
} else {
  markup = this.performInitialMount(renderedElement, hostParent, hostContainerInfo, transaction, context);
}

if (inst.componentDidMount) {
  if (process.env.NODE_ENV !== 'production') {
    transaction.getReactMountReady().enqueue(function () {
      measureLifeCyclePerf(function () {
        return inst.componentDidMount();
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent.performInitialMountWithErrorHandling"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>performInitialMountWithErrorHandling (renderedElement, hostParent, hostContainerInfo, transaction, context)](#apidoc.element.react-dom.ReactCompositeComponent.performInitialMountWithErrorHandling)
- description and source-code
```javascript
performInitialMountWithErrorHandling = function (renderedElement, hostParent, hostContainerInfo, transaction, context) {
  var markup;
  var checkpoint = transaction.checkpoint();
  try {
    markup = this.performInitialMount(renderedElement, hostParent, hostContainerInfo, transaction, context);
  } catch (e) {
    // Roll back to checkpoint, handle error (which may add items to the transaction), and take a new checkpoint
    transaction.rollback(checkpoint);
    this._instance.unstable_handleError(e);
    if (this._pendingStateQueue) {
      this._instance.state = this._processPendingState(this._instance.props, this._instance.context);
    }
    checkpoint = transaction.checkpoint();

    this._renderedComponent.unmountComponent(true);
    transaction.rollback(checkpoint);

    // Try again - we've informed the component about the error, so they can render an error message this time.
    // If this throws again, the error will bubble up (and can be caught by a higher error boundary).
    markup = this.performInitialMount(renderedElement, hostParent, hostContainerInfo, transaction, context);
  }
  return markup;
}
```
- example usage
```shell
...

this._pendingStateQueue = null;
this._pendingReplaceState = false;
this._pendingForceUpdate = false;

var markup;
if (inst.unstable_handleError) {
  markup = this.performInitialMountWithErrorHandling(renderedElement, hostParent, hostContainerInfo, transaction, context);
} else {
  markup = this.performInitialMount(renderedElement, hostParent, hostContainerInfo, transaction, context);
}

if (inst.componentDidMount) {
  if (process.env.NODE_ENV !== 'production') {
    transaction.getReactMountReady().enqueue(function () {
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent.performUpdateIfNecessary"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>performUpdateIfNecessary (transaction)](#apidoc.element.react-dom.ReactCompositeComponent.performUpdateIfNecessary)
- description and source-code
```javascript
performUpdateIfNecessary = function (transaction) {
  if (this._pendingElement != null) {
    ReactReconciler.receiveComponent(this, this._pendingElement, transaction, this._context);
  } else if (this._pendingStateQueue !== null || this._pendingForceUpdate) {
    this.updateComponent(transaction, this._currentElement, this._currentElement, this._context, this._context);
  } else {
    this._updateBatchNumber = null;
  }
}
```
- example usage
```shell
...
    return;
  }
  if (process.env.NODE_ENV !== 'production') {
    if (internalInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onBeforeUpdateComponent(internalInstance._debugID, internalInstance._currentElement);
    }
  }
  internalInstance.performUpdateIfNecessary(transaction);
  if (process.env.NODE_ENV !== 'production') {
    if (internalInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onUpdateComponent(internalInstance._debugID);
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent.receiveComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>receiveComponent (nextElement, transaction, nextContext)](#apidoc.element.react-dom.ReactCompositeComponent.receiveComponent)
- description and source-code
```javascript
receiveComponent = function (nextElement, transaction, nextContext) {
  var prevElement = this._currentElement;
  var prevContext = this._context;

  this._pendingElement = null;

  this.updateComponent(transaction, prevElement, nextElement, prevContext, nextContext);
}
```
- example usage
```shell
...
if (!nextChildren.hasOwnProperty(name)) {
  continue;
}
prevChild = prevChildren && prevChildren[name];
var prevElement = prevChild && prevChild._currentElement;
var nextElement = nextChildren[name];
if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
  ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
  nextChildren[name] = prevChild;
} else {
  if (prevChild) {
    removedNodes[name] = ReactReconciler.getHostNode(prevChild);
    ReactReconciler.unmountComponent(prevChild, false);
  }
  // The child must be instantiated before it's mounted.
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent.unmountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>unmountComponent (safely)](#apidoc.element.react-dom.ReactCompositeComponent.unmountComponent)
- description and source-code
```javascript
unmountComponent = function (safely) {
  if (!this._renderedComponent) {
    return;
  }

  var inst = this._instance;

  if (inst.componentWillUnmount && !inst._calledComponentWillUnmount) {
    inst._calledComponentWillUnmount = true;

    if (safely) {
      var name = this.getName() + '.componentWillUnmount()';
      ReactErrorUtils.invokeGuardedCallback(name, inst.componentWillUnmount.bind(inst));
    } else {
      if (process.env.NODE_ENV !== 'production') {
        measureLifeCyclePerf(function () {
          return inst.componentWillUnmount();
        }, this._debugID, 'componentWillUnmount');
      } else {
        inst.componentWillUnmount();
      }
    }
  }

  if (this._renderedComponent) {
    ReactReconciler.unmountComponent(this._renderedComponent, safely);
    this._renderedNodeType = null;
    this._renderedComponent = null;
    this._instance = null;
  }

  // Reset pending fields
  // Even if this component is scheduled for another update in ReactUpdates,
  // it would still be ignored because these fields are reset.
  this._pendingStateQueue = null;
  this._pendingReplaceState = false;
  this._pendingForceUpdate = false;
  this._pendingCallbacks = null;
  this._pendingElement = null;

  // These fields do not really need to be reset since this object is no
  // longer accessible.
  this._context = null;
  this._rootNodeID = 0;
  this._topLevelWrapper = null;

  // Delete the reference from the instance to this internal representation
  // which allow the internals to be properly cleaned up even if the user
  // leaks a reference to the public instance.
  ReactInstanceMap.remove(inst);

  // Some existing components rely on inst.props even after they've been
  // destroyed (in event handlers).
  // TODO: inst.props = null;
  // TODO: inst.state = null;
  // TODO: inst.context = null;
}
```
- example usage
```shell
...
var nextElement = nextChildren[name];
if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
  ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
  nextChildren[name] = prevChild;
} else {
  if (prevChild) {
    removedNodes[name] = ReactReconciler.getHostNode(prevChild);
    ReactReconciler.unmountComponent(prevChild, false);
  }
  // The child must be instantiated before it's mounted.
  var nextChildInstance = instantiateReactComponent(nextElement, true);
  nextChildren[name] = nextChildInstance;
  // Creating mount image now ensures refs are resolved in right order
  // (see https://github.com/facebook/react/pull/7101 for explanation).
  var nextChildMountImage = ReactReconciler.mountComponent(nextChildInstance, transaction, hostParent, hostContainerInfo, context
, selfDebugID);
...
```

#### <a name="apidoc.element.react-dom.ReactCompositeComponent.updateComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCompositeComponent.</span>updateComponent (transaction, prevParentElement, nextParentElement, prevUnmaskedContext, nextUnmaskedContext)](#apidoc.element.react-dom.ReactCompositeComponent.updateComponent)
- description and source-code
```javascript
updateComponent = function (transaction, prevParentElement, nextParentElement, prevUnmaskedContext, nextUnmaskedContext) {
  var inst = this._instance;
  !(inst != null) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Attempted to update component '%s' that has already
 been unmounted (or failed to mount).', this.getName() || 'ReactCompositeComponent') : _prodInvariant('136', this.getName() || '
ReactCompositeComponent') : void 0;

  var willReceive = false;
  var nextContext;

  // Determine if the context has changed or not
  if (this._context === nextUnmaskedContext) {
    nextContext = inst.context;
  } else {
    nextContext = this._processContext(nextUnmaskedContext);
    willReceive = true;
  }

  var prevProps = prevParentElement.props;
  var nextProps = nextParentElement.props;

  // Not a simple state update but a props update
  if (prevParentElement !== nextParentElement) {
    willReceive = true;
  }

  // An update here will schedule an update but immediately set
  // _pendingStateQueue which will ensure that any state updates gets
  // immediately reconciled instead of waiting for the next batch.
  if (willReceive && inst.componentWillReceiveProps) {
    if (process.env.NODE_ENV !== 'production') {
      measureLifeCyclePerf(function () {
        return inst.componentWillReceiveProps(nextProps, nextContext);
      }, this._debugID, 'componentWillReceiveProps');
    } else {
      inst.componentWillReceiveProps(nextProps, nextContext);
    }
  }

  var nextState = this._processPendingState(nextProps, nextContext);
  var shouldUpdate = true;

  if (!this._pendingForceUpdate) {
    if (inst.shouldComponentUpdate) {
      if (process.env.NODE_ENV !== 'production') {
        shouldUpdate = measureLifeCyclePerf(function () {
          return inst.shouldComponentUpdate(nextProps, nextState, nextContext);
        }, this._debugID, 'shouldComponentUpdate');
      } else {
        shouldUpdate = inst.shouldComponentUpdate(nextProps, nextState, nextContext);
      }
    } else {
      if (this._compositeType === CompositeTypes.PureClass) {
        shouldUpdate = !shallowEqual(prevProps, nextProps) || !shallowEqual(inst.state, nextState);
      }
    }
  }

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(shouldUpdate !== undefined, '%s.shouldComponentUpdate(): Returned undefined
instead of a ' + 'boolean value. Make sure to return true or false.', this.getName() || 'ReactCompositeComponent') : void 0;
  }

  this._updateBatchNumber = null;
  if (shouldUpdate) {
    this._pendingForceUpdate = false;
    // Will set 'this.props', 'this.state' and 'this.context'.
    this._performComponentUpdate(nextParentElement, nextProps, nextState, nextContext, transaction, nextUnmaskedContext);
  } else {
    // If it's determined that a component should not update, we still want
    // to set props and state but we shortcut the rest of the update.
    this._currentElement = nextParentElement;
    this._context = nextUnmaskedContext;
    inst.props = nextProps;
    inst.state = nextState;
    inst.context = nextContext;
  }
}
```
- example usage
```shell
...

receiveComponent: function (nextElement, transaction, nextContext) {
  var prevElement = this._currentElement;
  var prevContext = this._context;

  this._pendingElement = null;

  this.updateComponent(transaction, prevElement, nextElement, prevContext, nextContext);
},

/**
 * If any of '_pendingElement', '_pendingStateQueue', or '_pendingForceUpdate'
 * is set, update the component.
 *
 * @param {ReactReconcileTransaction} transaction
...
```



# <a name="apidoc.module.react-dom.ReactCoroutine"></a>[module react-dom.ReactCoroutine](#apidoc.module.react-dom.ReactCoroutine)

#### <a name="apidoc.element.react-dom.ReactCoroutine.createCoroutine"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCoroutine.</span>createCoroutine (children, handler, props)](#apidoc.element.react-dom.ReactCoroutine.createCoroutine)
- description and source-code
```javascript
createCoroutine = function (children, handler, props) {
  var key = arguments.length > 3 && arguments[3] !== undefined ? arguments[3] : null;

  var coroutine = {
    // This tag allow us to uniquely identify this as a React Coroutine
    $$typeof: REACT_COROUTINE_TYPE,
    key: key == null ? null : '' + key,
    children: children,
    handler: handler,
    props: props
  };

  if (process.env.NODE_ENV !== 'production') {
    // TODO: Add _store property for marking this as validated.
    if (Object.freeze) {
      Object.freeze(coroutine.props);
      Object.freeze(coroutine);
    }
  }

  return coroutine;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactCoroutine.createYield"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCoroutine.</span>createYield (props, continuation)](#apidoc.element.react-dom.ReactCoroutine.createYield)
- description and source-code
```javascript
createYield = function (props, continuation) {
  var key = arguments.length > 2 && arguments[2] !== undefined ? arguments[2] : null;

  var yieldNode = {
    // This tag allow us to uniquely identify this as a React Yield
    $$typeof: REACT_YIELD_TYPE,
    key: key == null ? null : '' + key,
    props: props,
    continuation: continuation
  };

  if (process.env.NODE_ENV !== 'production') {
    // TODO: Add _store property for marking this as validated.
    if (Object.freeze) {
      Object.freeze(yieldNode.props);
      Object.freeze(yieldNode);
    }
  }

  return yieldNode;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactCoroutine.isCoroutine"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCoroutine.</span>isCoroutine (object)](#apidoc.element.react-dom.ReactCoroutine.isCoroutine)
- description and source-code
```javascript
isCoroutine = function (object) {
  return typeof object === 'object' && object !== null && object.$$typeof === REACT_COROUTINE_TYPE;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactCoroutine.isYield"></a>[function <span class="apidocSignatureSpan">react-dom.ReactCoroutine.</span>isYield (object)](#apidoc.element.react-dom.ReactCoroutine.isYield)
- description and source-code
```javascript
isYield = function (object) {
  return typeof object === 'object' && object !== null && object.$$typeof === REACT_YIELD_TYPE;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactDOMComponent"></a>[module react-dom.ReactDOMComponent](#apidoc.module.react-dom.ReactDOMComponent)

#### <a name="apidoc.element.react-dom.ReactDOMComponent.ReactDOMComponent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ReactDOMComponent (element)](#apidoc.element.react-dom.ReactDOMComponent.ReactDOMComponent)
- description and source-code
```javascript
function ReactDOMComponent(element) {
  var tag = element.type;
  validateDangerousTag(tag);
  this._currentElement = element;
  this._tag = tag.toLowerCase();
  this._namespaceURI = null;
  this._renderedChildren = null;
  this._previousStyle = null;
  this._previousStyleCopy = null;
  this._hostNode = null;
  this._hostParent = null;
  this._rootNodeID = 0;
  this._domID = 0;
  this._hostContainerInfo = null;
  this._wrapperState = null;
  this._topLevelWrapper = null;
  this._flags = 0;
  if (process.env.NODE_ENV !== 'production') {
    this._ancestorInfo = null;
    setAndValidateContentChildDev.call(this, null);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactDOMComponent.prototype"></a>[module react-dom.ReactDOMComponent.prototype](#apidoc.module.react-dom.ReactDOMComponent.prototype)

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype._createContentMarkup"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_createContentMarkup (transaction, props, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype._createContentMarkup)
- description and source-code
```javascript
_createContentMarkup = function (transaction, props, context) {
  var ret = '';

  // Intentional use of != to avoid catching zero/false.
  var innerHTML = props.dangerouslySetInnerHTML;
  if (innerHTML != null) {
    if (innerHTML.__html != null) {
      ret = innerHTML.__html;
    }
  } else {
    var contentToUse = CONTENT_TYPES[typeof props.children] ? props.children : null;
    var childrenToUse = contentToUse != null ? null : props.children;
    if (contentToUse != null) {
      // TODO: Validate that text is allowed as a child of this node
      ret = escapeTextContentForBrowser(contentToUse);
      if (process.env.NODE_ENV !== 'production') {
        setAndValidateContentChildDev.call(this, contentToUse);
      }
    } else if (childrenToUse != null) {
      var mountImages = this.mountChildren(childrenToUse, transaction, context);
      ret = mountImages.join('');
    }
  }
  if (newlineEatingTags[this._tag] && ret.charAt(0) === '\n') {
    // text/html ignores the first character in these tags if it's a newline
    // Prefer to break application/xml over text/html (for now) by adding
    // a newline specifically to get eaten by the parser. (Alternately for
    // textareas, replacing "^\n" with "\r\n" doesn't get eaten, and the first
    // \r is normalized out by HTMLTextAreaElement#value.)
    // See: <http://www.w3.org/TR/html-polyglot/#newlines-in-textarea-and-pre>
    // See: <http://www.w3.org/TR/html5/syntax.html#element-restrictions>
    // See: <http://www.w3.org/TR/html5/syntax.html#newlines>
    // See: Parsing of "textarea" "listing" and "pre" elements
    //  from <http://www.w3.org/TR/html5/syntax.html#parsing-main-inbody>
    return '\n' + ret;
  } else {
    return ret;
  }
}
```
- example usage
```shell
...
  }
  this._updateDOMProperties(null, props, transaction);
  var lazyTree = DOMLazyTree(el);
  this._createInitialChildren(transaction, props, context, lazyTree);
  mountImage = lazyTree;
} else {
  var tagOpen = this._createOpenTagMarkupAndPutListeners(transaction, props);
  var tagContent = this._createContentMarkup(transaction, props, context);
  if (!tagContent && omittedCloseTags[this._tag]) {
    mountImage = tagOpen + '/>';
  } else {
    mountImage = tagOpen + '>' + tagContent + '</' + this._currentElement.type + '>';
  }
}
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype._createInitialChildren"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_createInitialChildren (transaction, props, context, lazyTree)](#apidoc.element.react-dom.ReactDOMComponent.prototype._createInitialChildren)
- description and source-code
```javascript
_createInitialChildren = function (transaction, props, context, lazyTree) {
  // Intentional use of != to avoid catching zero/false.
  var innerHTML = props.dangerouslySetInnerHTML;
  if (innerHTML != null) {
    if (innerHTML.__html != null) {
      DOMLazyTree.queueHTML(lazyTree, innerHTML.__html);
    }
  } else {
    var contentToUse = CONTENT_TYPES[typeof props.children] ? props.children : null;
    var childrenToUse = contentToUse != null ? null : props.children;
    // TODO: Validate that text is allowed as a child of this node
    if (contentToUse != null) {
      // Avoid setting textContent when the text is empty. In IE11 setting
      // textContent on a text area will cause the placeholder to not
      // show within the textarea until it has been focused and blurred again.
      // https://github.com/facebook/react/issues/6731#issuecomment-254874553
      if (contentToUse !== '') {
        if (process.env.NODE_ENV !== 'production') {
          setAndValidateContentChildDev.call(this, contentToUse);
        }
        DOMLazyTree.queueText(lazyTree, contentToUse);
      }
    } else if (childrenToUse != null) {
      var mountImages = this.mountChildren(childrenToUse, transaction, context);
      for (var i = 0; i < mountImages.length; i++) {
        DOMLazyTree.queueChild(lazyTree, mountImages[i]);
      }
    }
  }
}
```
- example usage
```shell
...
  ReactDOMComponentTree.precacheNode(this, el);
  this._flags |= Flags.hasCachedChildNodes;
  if (!this._hostParent) {
    DOMPropertyOperations.setAttributeForRoot(el);
  }
  this._updateDOMProperties(null, props, transaction);
  var lazyTree = DOMLazyTree(el);
  this._createInitialChildren(transaction, props, context, lazyTree);
  mountImage = lazyTree;
} else {
  var tagOpen = this._createOpenTagMarkupAndPutListeners(transaction, props);
  var tagContent = this._createContentMarkup(transaction, props, context);
  if (!tagContent && omittedCloseTags[this._tag]) {
    mountImage = tagOpen + '/>';
  } else {
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype._createOpenTagMarkupAndPutListeners"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_createOpenTagMarkupAndPutListeners (transaction, props)](#apidoc.element.react-dom.ReactDOMComponent.prototype._createOpenTagMarkupAndPutListeners)
- description and source-code
```javascript
_createOpenTagMarkupAndPutListeners = function (transaction, props) {
  var ret = '<' + this._currentElement.type;

  for (var propKey in props) {
    if (!props.hasOwnProperty(propKey)) {
      continue;
    }
    var propValue = props[propKey];
    if (propValue == null) {
      continue;
    }
    if (registrationNameModules.hasOwnProperty(propKey)) {
      if (propValue) {
        enqueuePutListener(this, propKey, propValue, transaction);
      }
    } else {
      if (propKey === STYLE) {
        if (propValue) {
          if (process.env.NODE_ENV !== 'production') {
            // See '_updateDOMProperties'. style block
            this._previousStyle = propValue;
          }
          propValue = this._previousStyleCopy = _assign({}, props.style);
        }
        propValue = CSSPropertyOperations.createMarkupForStyles(propValue, this);
      }
      var markup = null;
      if (this._tag != null && isCustomComponent(this._tag, props)) {
        if (!RESERVED_PROPS.hasOwnProperty(propKey)) {
          markup = DOMPropertyOperations.createMarkupForCustomAttribute(propKey, propValue);
        }
      } else {
        markup = DOMPropertyOperations.createMarkupForProperty(propKey, propValue);
      }
      if (markup) {
        ret += ' ' + markup;
      }
    }
  }

  // For static pages, no need to put React ID and checksum. Saves lots of
  // bytes.
  if (transaction.renderToStaticMarkup) {
    return ret;
  }

  if (!this._hostParent) {
    ret += ' ' + DOMPropertyOperations.createMarkupForRoot();
  }
  ret += ' ' + DOMPropertyOperations.createMarkupForID(this._domID);
  return ret;
}
```
- example usage
```shell
...
    DOMPropertyOperations.setAttributeForRoot(el);
  }
  this._updateDOMProperties(null, props, transaction);
  var lazyTree = DOMLazyTree(el);
  this._createInitialChildren(transaction, props, context, lazyTree);
  mountImage = lazyTree;
} else {
  var tagOpen = this._createOpenTagMarkupAndPutListeners(transaction, props);
  var tagContent = this._createContentMarkup(transaction, props, context);
  if (!tagContent && omittedCloseTags[this._tag]) {
    mountImage = tagOpen + '/>';
  } else {
    mountImage = tagOpen + '>' + tagContent + '</' + this._currentElement.type + '>';
  }
}
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype._mountChildAtIndex"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_mountChildAtIndex (child, mountImage, afterNode, index, transaction, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype._mountChildAtIndex)
- description and source-code
```javascript
_mountChildAtIndex = function (child, mountImage, afterNode, index, transaction, context) {
  child._mountIndex = index;
  return this.createChild(child, afterNode, mountImage);
}
```
- example usage
```shell
...
  } else {
    if (prevChild) {
      // Update 'lastIndex' before '_mountIndex' gets unset by unmounting.
      lastIndex = Math.max(prevChild._mountIndex, lastIndex);
      // The 'removedNodes' loop below will actually remove the child.
    }
    // The child must be instantiated before it's mounted.
    updates = enqueue(updates, this._mountChildAtIndex(nextChild, mountImages[nextMountIndex], lastPlacedNode, nextIndex, transaction
, context));
    nextMountIndex++;
  }
  nextIndex++;
  lastPlacedNode = ReactReconciler.getHostNode(nextChild);
}
// Remove children that are no longer present.
for (name in removedNodes) {
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype._reconcilerInstantiateChildren"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_reconcilerInstantiateChildren (nestedChildren, transaction, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype._reconcilerInstantiateChildren)
- description and source-code
```javascript
_reconcilerInstantiateChildren = function (nestedChildren, transaction, context) {
  if (process.env.NODE_ENV !== 'production') {
    var selfDebugID = getDebugID(this);
    if (this._currentElement) {
      try {
        ReactCurrentOwner.current = this._currentElement._owner;
        return ReactChildReconciler.instantiateChildren(nestedChildren, transaction, context, selfDebugID);
      } finally {
        ReactCurrentOwner.current = null;
      }
    }
  }
  return ReactChildReconciler.instantiateChildren(nestedChildren, transaction, context);
}
```
- example usage
```shell
...
     * of 'ReactDOMComponent', a mount image is a string of markup.
     *
     * @param {?object} nestedChildren Nested child maps.
     * @return {array} An array of mounted representations.
     * @internal
     */
    mountChildren: function (nestedChildren, transaction, context) {
var children = this._reconcilerInstantiateChildren(nestedChildren, transaction, context);
this._renderedChildren = children;

var mountImages = [];
var index = 0;
for (var name in children) {
  if (children.hasOwnProperty(name)) {
    var child = children[name];
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype._reconcilerUpdateChildren"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_reconcilerUpdateChildren (prevChildren, nextNestedChildrenElements, mountImages, removedNodes, transaction, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype._reconcilerUpdateChildren)
- description and source-code
```javascript
_reconcilerUpdateChildren = function (prevChildren, nextNestedChildrenElements, mountImages, removedNodes, transaction, context) {
  var nextChildren;
  var selfDebugID = 0;
  if (process.env.NODE_ENV !== 'production') {
    selfDebugID = getDebugID(this);
    if (this._currentElement) {
      try {
        ReactCurrentOwner.current = this._currentElement._owner;
        nextChildren = flattenChildren(nextNestedChildrenElements, selfDebugID);
      } finally {
        ReactCurrentOwner.current = null;
      }
      ReactChildReconciler.updateChildren(prevChildren, nextChildren, mountImages, removedNodes, transaction, this, this._hostContainerInfo
, context, selfDebugID);
      return nextChildren;
    }
  }
  nextChildren = flattenChildren(nextNestedChildrenElements, selfDebugID);
  ReactChildReconciler.updateChildren(prevChildren, nextChildren, mountImages, removedNodes, transaction, this, this._hostContainerInfo
, context, selfDebugID);
  return nextChildren;
}
```
- example usage
```shell
...
 * @final
 * @protected
 */
_updateChildren: function (nextNestedChildrenElements, transaction, context) {
  var prevChildren = this._renderedChildren;
  var removedNodes = {};
  var mountImages = [];
  var nextChildren = this._reconcilerUpdateChildren(prevChildren, nextNestedChildrenElements, mountImages, removedNodes, transaction
, context);
  if (!nextChildren && !prevChildren) {
    return;
  }
  var updates = null;
  var name;
  // 'nextIndex' will increment for each child in 'nextChildren', but
  // 'lastIndex' will be the last index visited in 'prevChildren'.
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype._unmountChild"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_unmountChild (child, node)](#apidoc.element.react-dom.ReactDOMComponent.prototype._unmountChild)
- description and source-code
```javascript
_unmountChild = function (child, node) {
  var update = this.removeChild(child, node);
  child._mountIndex = null;
  return update;
}
```
- example usage
```shell
...
  }
  nextIndex++;
  lastPlacedNode = ReactReconciler.getHostNode(nextChild);
}
// Remove children that are no longer present.
for (name in removedNodes) {
  if (removedNodes.hasOwnProperty(name)) {
    updates = enqueue(updates, this._unmountChild(prevChildren[name], removedNodes[name]));
  }
}
if (updates) {
  processQueue(this, updates);
}
this._renderedChildren = nextChildren;
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype._updateChildren"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_updateChildren (nextNestedChildrenElements, transaction, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype._updateChildren)
- description and source-code
```javascript
_updateChildren = function (nextNestedChildrenElements, transaction, context) {
  var prevChildren = this._renderedChildren;
  var removedNodes = {};
  var mountImages = [];
  var nextChildren = this._reconcilerUpdateChildren(prevChildren, nextNestedChildrenElements, mountImages, removedNodes, transaction
, context);
  if (!nextChildren && !prevChildren) {
    return;
  }
  var updates = null;
  var name;
  // 'nextIndex' will increment for each child in 'nextChildren', but
  // 'lastIndex' will be the last index visited in 'prevChildren'.
  var nextIndex = 0;
  var lastIndex = 0;
  // 'nextMountIndex' will increment for each newly mounted child.
  var nextMountIndex = 0;
  var lastPlacedNode = null;
  for (name in nextChildren) {
    if (!nextChildren.hasOwnProperty(name)) {
      continue;
    }
    var prevChild = prevChildren && prevChildren[name];
    var nextChild = nextChildren[name];
    if (prevChild === nextChild) {
      updates = enqueue(updates, this.moveChild(prevChild, lastPlacedNode, nextIndex, lastIndex));
      lastIndex = Math.max(prevChild._mountIndex, lastIndex);
      prevChild._mountIndex = nextIndex;
    } else {
      if (prevChild) {
        // Update 'lastIndex' before '_mountIndex' gets unset by unmounting.
        lastIndex = Math.max(prevChild._mountIndex, lastIndex);
        // The 'removedNodes' loop below will actually remove the child.
      }
      // The child must be instantiated before it's mounted.
      updates = enqueue(updates, this._mountChildAtIndex(nextChild, mountImages[nextMountIndex], lastPlacedNode, nextIndex, transaction
, context));
      nextMountIndex++;
    }
    nextIndex++;
    lastPlacedNode = ReactReconciler.getHostNode(nextChild);
  }
  // Remove children that are no longer present.
  for (name in removedNodes) {
    if (removedNodes.hasOwnProperty(name)) {
      updates = enqueue(updates, this._unmountChild(prevChildren[name], removedNodes[name]));
    }
  }
  if (updates) {
    processQueue(this, updates);
  }
  this._renderedChildren = nextChildren;

  if (process.env.NODE_ENV !== 'production') {
    setChildrenForInstrumentation.call(this, nextChildren);
  }
}
```
- example usage
```shell
...
 *
 * @param {?object} nextNestedChildrenElements Nested child element maps.
 * @param {ReactReconcileTransaction} transaction
 * @internal
 */
updateChildren: function (nextNestedChildrenElements, transaction, context) {
  // Hook used by React ART
  this._updateChildren(nextNestedChildrenElements, transaction, context);
},

/**
 * @param {?object} nextNestedChildrenElements Nested child element maps.
 * @param {ReactReconcileTransaction} transaction
 * @final
 * @protected
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype._updateDOMChildren"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_updateDOMChildren (lastProps, nextProps, transaction, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype._updateDOMChildren)
- description and source-code
```javascript
_updateDOMChildren = function (lastProps, nextProps, transaction, context) {
  var lastContent = CONTENT_TYPES[typeof lastProps.children] ? lastProps.children : null;
  var nextContent = CONTENT_TYPES[typeof nextProps.children] ? nextProps.children : null;

  var lastHtml = lastProps.dangerouslySetInnerHTML && lastProps.dangerouslySetInnerHTML.__html;
  var nextHtml = nextProps.dangerouslySetInnerHTML && nextProps.dangerouslySetInnerHTML.__html;

  // Note the use of '!=' which checks for null or undefined.
  var lastChildren = lastContent != null ? null : lastProps.children;
  var nextChildren = nextContent != null ? null : nextProps.children;

  // If we're switching from children to content/html or vice versa, remove
  // the old content
  var lastHasContentOrHtml = lastContent != null || lastHtml != null;
  var nextHasContentOrHtml = nextContent != null || nextHtml != null;
  if (lastChildren != null && nextChildren == null) {
    this.updateChildren(null, transaction, context);
  } else if (lastHasContentOrHtml && !nextHasContentOrHtml) {
    this.updateTextContent('');
    if (process.env.NODE_ENV !== 'production') {
      ReactInstrumentation.debugTool.onSetChildren(this._debugID, []);
    }
  }

  if (nextContent != null) {
    if (lastContent !== nextContent) {
      this.updateTextContent('' + nextContent);
      if (process.env.NODE_ENV !== 'production') {
        setAndValidateContentChildDev.call(this, nextContent);
      }
    }
  } else if (nextHtml != null) {
    if (lastHtml !== nextHtml) {
      this.updateMarkup('' + nextHtml);
    }
    if (process.env.NODE_ENV !== 'production') {
      ReactInstrumentation.debugTool.onSetChildren(this._debugID, []);
    }
  } else if (nextChildren != null) {
    if (process.env.NODE_ENV !== 'production') {
      setAndValidateContentChildDev.call(this, null);
    }

    this.updateChildren(nextChildren, transaction, context);
  }
}
```
- example usage
```shell
...
    lastProps = ReactDOMTextarea.getHostProps(this, lastProps);
    nextProps = ReactDOMTextarea.getHostProps(this, nextProps);
    break;
}

assertValidProps(this, nextProps);
this._updateDOMProperties(lastProps, nextProps, transaction);
this._updateDOMChildren(lastProps, nextProps, transaction, context);

switch (this._tag) {
  case 'input':
    // Update the wrapper around inputs *after* updating props. This has to
    // happen after '_updateDOMProperties'. Otherwise HTML5 input validations
    // raise warnings and prevent the new value from being assigned.
    ReactDOMInput.updateWrapper(this);
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype._updateDOMProperties"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>_updateDOMProperties (lastProps, nextProps, transaction)](#apidoc.element.react-dom.ReactDOMComponent.prototype._updateDOMProperties)
- description and source-code
```javascript
_updateDOMProperties = function (lastProps, nextProps, transaction) {
  var propKey;
  var styleName;
  var styleUpdates;
  for (propKey in lastProps) {
    if (nextProps.hasOwnProperty(propKey) || !lastProps.hasOwnProperty(propKey) || lastProps[propKey] == null) {
      continue;
    }
    if (propKey === STYLE) {
      var lastStyle = this._previousStyleCopy;
      for (styleName in lastStyle) {
        if (lastStyle.hasOwnProperty(styleName)) {
          styleUpdates = styleUpdates || {};
          styleUpdates[styleName] = '';
        }
      }
      this._previousStyleCopy = null;
    } else if (registrationNameModules.hasOwnProperty(propKey)) {
      if (lastProps[propKey]) {
        // Only call deleteListener if there was a listener previously or
        // else willDeleteListener gets called when there wasn't actually a
        // listener (e.g., onClick={null})
        deleteListener(this, propKey);
      }
    } else if (isCustomComponent(this._tag, lastProps)) {
      if (!RESERVED_PROPS.hasOwnProperty(propKey)) {
        DOMPropertyOperations.deleteValueForAttribute(getNode(this), propKey);
      }
    } else if (DOMProperty.properties[propKey] || DOMProperty.isCustomAttribute(propKey)) {
      DOMPropertyOperations.deleteValueForProperty(getNode(this), propKey);
    }
  }
  for (propKey in nextProps) {
    var nextProp = nextProps[propKey];
    var lastProp = propKey === STYLE ? this._previousStyleCopy : lastProps != null ? lastProps[propKey] : undefined;
    if (!nextProps.hasOwnProperty(propKey) || nextProp === lastProp || nextProp == null && lastProp == null) {
      continue;
    }
    if (propKey === STYLE) {
      if (nextProp) {
        if (process.env.NODE_ENV !== 'production') {
          checkAndWarnForMutatedStyle(this._previousStyleCopy, this._previousStyle, this);
          this._previousStyle = nextProp;
        }
        nextProp = this._previousStyleCopy = _assign({}, nextProp);
      } else {
        this._previousStyleCopy = null;
      }
      if (lastProp) {
        // Unset styles on 'lastProp' but not on 'nextProp'.
        for (styleName in lastProp) {
          if (lastProp.hasOwnProperty(styleName) && (!nextProp || !nextProp.hasOwnProperty(styleName))) {
            styleUpdates = styleUpdates || {};
            styleUpdates[styleName] = '';
          }
        }
        // Update styles that changed since 'lastProp'.
        for (styleName in nextProp) {
          if (nextProp.hasOwnProperty(styleName) && lastProp[styleName] !== nextProp[styleName]) {
            styleUpdates = styleUpdates || {};
            styleUpdates[styleName] = nextProp[styleName];
          }
        }
      } else {
        // Relies on 'updateStylesByID' not mutating 'styleUpdates'.
        styleUpdates = nextProp;
      }
    } else if (registrationNameModules.hasOwnProperty(propKey)) {
      if (nextProp) {
        enqueuePutListener(this, propKey, nextProp, transaction);
      } else if (lastProp) {
        deleteListener(this, propKey);
      }
    } else if (isCustomComponent(this._tag, nextProps)) {
      if (!RESERVED_PROPS.hasOwnProperty(propKey)) {
        DOMPropertyOperations.setValueForAttribute(getNode(this), propKey, nextProp);
      }
    } else if (DOMProperty.properties[propKey] || DOMProperty.isCustomAttribute(propKey)) {
      var node = getNode(this);
      // If we're updating to null or undefined, we should remove the property
      // from the DOM node instead of inadvertently setting to a string. This
      // brings us in line with the same behavior we have on initial render.
      if (nextProp != null) {
        DOMPropertyOperations.setValueForProperty(node, propKey, nextProp);
      } else {
        DOMPropertyOperations.deleteValueForProperty(node, propKey);
      }
    }
  }
  if (styleUpdates) {
    CSSPropertyOperations.setValueForStyles(getNode(this), styleUpdates, this);
  }
}
```
- example usage
```shell
...
    el = ownerDocument.createElementNS(namespaceURI, this._currentElement.type);
  }
  ReactDOMComponentTree.precacheNode(this, el);
  this._flags |= Flags.hasCachedChildNodes;
  if (!this._hostParent) {
    DOMPropertyOperations.setAttributeForRoot(el);
  }
  this._updateDOMProperties(null, props, transaction);
  var lazyTree = DOMLazyTree(el);
  this._createInitialChildren(transaction, props, context, lazyTree);
  mountImage = lazyTree;
} else {
  var tagOpen = this._createOpenTagMarkupAndPutListeners(transaction, props);
  var tagContent = this._createContentMarkup(transaction, props, context);
  if (!tagContent && omittedCloseTags[this._tag]) {
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype.createChild"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>createChild (child, afterNode, mountImage)](#apidoc.element.react-dom.ReactDOMComponent.prototype.createChild)
- description and source-code
```javascript
createChild = function (child, afterNode, mountImage) {
  return makeInsertMarkup(mountImage, afterNode, child._mountIndex);
}
```
- example usage
```shell
...
 * @param {string} name Name of the child.
 * @param {number} index Index at which to insert the child.
 * @param {ReactReconcileTransaction} transaction
 * @private
 */
_mountChildAtIndex: function (child, mountImage, afterNode, index, transaction, context) {
  child._mountIndex = index;
  return this.createChild(child, afterNode, mountImage);
},

/**
 * Unmounts a rendered child.
 *
 * NOTE: This is part of 'updateChildren' and is here for readability.
 *
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype.getHostNode"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>getHostNode ()](#apidoc.element.react-dom.ReactDOMComponent.prototype.getHostNode)
- description and source-code
```javascript
getHostNode = function () {
  return getNode(this);
}
```
- example usage
```shell
...
var prevElement = prevChild && prevChild._currentElement;
var nextElement = nextChildren[name];
if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
  ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
  nextChildren[name] = prevChild;
} else {
  if (prevChild) {
    removedNodes[name] = ReactReconciler.getHostNode(prevChild);
    ReactReconciler.unmountComponent(prevChild, false);
  }
  // The child must be instantiated before it's mounted.
  var nextChildInstance = instantiateReactComponent(nextElement, true);
  nextChildren[name] = nextChildInstance;
  // Creating mount image now ensures refs are resolved in right order
  // (see https://github.com/facebook/react/pull/7101 for explanation).
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype.getPublicInstance"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>getPublicInstance ()](#apidoc.element.react-dom.ReactDOMComponent.prototype.getPublicInstance)
- description and source-code
```javascript
getPublicInstance = function () {
  return getNode(this);
}
```
- example usage
```shell
...
 *
 * @param {string} ref Reference name.
 * @param {component} component Component to store as 'ref'.
 * @final
 * @private
 */
attachRef: function (ref, component) {
  var inst = this.getPublicInstance();
  !(inst != null) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Stateless function components cannot have refs.') :
_prodInvariant('110') : void 0;
  var publicComponentInstance = component.getPublicInstance();
  if (process.env.NODE_ENV !== 'production') {
    var componentName = component && component.getName ? component.getName() : 'a component';
    process.env.NODE_ENV !== 'production' ? warning(publicComponentInstance != null || component._compositeType !== CompositeTypes
.StatelessFunctional, 'Stateless function components cannot be given refs ' + '(See ref "%s" in %s created by %s). ' + 'Attempts
 to access this ref will fail.', ref, componentName, this.getName()) : void 0;
  }
  var refs = inst.refs === emptyObject ? inst.refs = {} : inst.refs;
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype.mountChildren"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>mountChildren (nestedChildren, transaction, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype.mountChildren)
- description and source-code
```javascript
mountChildren = function (nestedChildren, transaction, context) {
  var children = this._reconcilerInstantiateChildren(nestedChildren, transaction, context);
  this._renderedChildren = children;

  var mountImages = [];
  var index = 0;
  for (var name in children) {
    if (children.hasOwnProperty(name)) {
      var child = children[name];
      var selfDebugID = 0;
      if (process.env.NODE_ENV !== 'production') {
        selfDebugID = getDebugID(this);
      }
      var mountImage = ReactReconciler.mountComponent(child, transaction, this, this._hostContainerInfo, context, selfDebugID);
      child._mountIndex = index++;
      mountImages.push(mountImage);
    }
  }

  if (process.env.NODE_ENV !== 'production') {
    setChildrenForInstrumentation.call(this, children);
  }

  return mountImages;
}
```
- example usage
```shell
...
  if (contentToUse != null) {
    // TODO: Validate that text is allowed as a child of this node
    ret = escapeTextContentForBrowser(contentToUse);
    if (process.env.NODE_ENV !== 'production') {
      setAndValidateContentChildDev.call(this, contentToUse);
    }
  } else if (childrenToUse != null) {
    var mountImages = this.mountChildren(childrenToUse, transaction, context);
    ret = mountImages.join('');
  }
}
if (newlineEatingTags[this._tag] && ret.charAt(0) === '\n') {
  // text/html ignores the first character in these tags if it's a newline
  // Prefer to break application/xml over text/html (for now) by adding
  // a newline specifically to get eaten by the parser. (Alternately for
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype.mountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>mountComponent (transaction, hostParent, hostContainerInfo, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype.mountComponent)
- description and source-code
```javascript
mountComponent = function (transaction, hostParent, hostContainerInfo, context) {
  this._rootNodeID = globalIdCounter++;
  this._domID = hostContainerInfo._idCounter++;
  this._hostParent = hostParent;
  this._hostContainerInfo = hostContainerInfo;

  var props = this._currentElement.props;

  switch (this._tag) {
    case 'audio':
    case 'form':
    case 'iframe':
    case 'img':
    case 'link':
    case 'object':
    case 'source':
    case 'video':
      this._wrapperState = {
        listeners: null
      };
      transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
      break;
    case 'input':
      ReactDOMInput.mountWrapper(this, props, hostParent);
      props = ReactDOMInput.getHostProps(this, props);
      transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
      break;
    case 'option':
      ReactDOMOption.mountWrapper(this, props, hostParent);
      props = ReactDOMOption.getHostProps(this, props);
      break;
    case 'select':
      ReactDOMSelect.mountWrapper(this, props, hostParent);
      props = ReactDOMSelect.getHostProps(this, props);
      transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
      break;
    case 'textarea':
      ReactDOMTextarea.mountWrapper(this, props, hostParent);
      props = ReactDOMTextarea.getHostProps(this, props);
      transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
      break;
  }

  assertValidProps(this, props);

  // We create tags in the namespace of their parent container, except HTML
  // tags get no namespace.
  var namespaceURI;
  var parentTag;
  if (hostParent != null) {
    namespaceURI = hostParent._namespaceURI;
    parentTag = hostParent._tag;
  } else if (hostContainerInfo._tag) {
    namespaceURI = hostContainerInfo._namespaceURI;
    parentTag = hostContainerInfo._tag;
  }
  if (namespaceURI == null || namespaceURI === DOMNamespaces.svg && parentTag === 'foreignobject') {
    namespaceURI = DOMNamespaces.html;
  }
  if (namespaceURI === DOMNamespaces.html) {
    if (this._tag === 'svg') {
      namespaceURI = DOMNamespaces.svg;
    } else if (this._tag === 'math') {
      namespaceURI = DOMNamespaces.mathml;
    }
  }
  this._namespaceURI = namespaceURI;

  if (process.env.NODE_ENV !== 'production') {
    var parentInfo;
    if (hostParent != null) {
      parentInfo = hostParent._ancestorInfo;
    } else if (hostContainerInfo._tag) {
      parentInfo = hostContainerInfo._ancestorInfo;
    }
    if (parentInfo) {
      // parentInfo should always be present except for the top-level
      // component when server rendering
      validateDOMNesting(this._tag, null, this, parentInfo);
    }
    this._ancestorInfo = validateDOMNesting.updatedAncestorInfo(parentInfo, this._tag, this);
  }

  var mountImage;
  if (transaction.useCreateElement) {
    var ownerDocument = hostContainerInfo._ownerDocument;
    var el;
    if (namespaceURI === DOMNamespaces.html) {
      if (this._tag === 'script') {
        // Create the script via .innerHTML so its "parser-inserted" flag is
        // set to true and it does not execute
        var div = ownerDocument.createElement('div');
        var type = this._currentElement.type;
        div.innerHTML = '<' + type + '></' + type + '>';
        el = div.removeChild(div.firstChild);
      } else if (props.is) {
        el = ownerDocument.createElement(this._currentElement.type, props.is);
      } else {
        // Separate else branch instead of using 'props.is || undefined' above becuase of a Firefox bug.
        // See discussion in https://github.com/facebook/react/pull/6896
        // and discussion in https://bugzilla.mozilla.org/show_bug.cgi?id=1276240
        el = ownerDocument.createElement(this._currentElement.type);
      }
    } else {
      el = ownerDocument.createElementNS(namespaceURI, this._currentElement.type);
    }
    ReactDOMComponentTree.precacheNode(this, el);
    this._flags |= Flags.hasCachedChildNodes;
    if (!this._hostParent) {
      DOMPropertyOperations.setAttributeForRoot(el);
    }
    this._updateDOMProperties(null, pr ...
```
- example usage
```shell
...
      ReactReconciler.unmountComponent(prevChild, false);
    }
    // The child must be instantiated before it's mounted.
    var nextChildInstance = instantiateReactComponent(nextElement, true);
    nextChildren[name] = nextChildInstance;
    // Creating mount image now ensures refs are resolved in right order
    // (see https://github.com/facebook/react/pull/7101 for explanation).
    var nextChildMountImage = ReactReconciler.mountComponent(nextChildInstance, transaction, hostParent, hostContainerInfo, context
, selfDebugID);
    mountImages.push(nextChildMountImage);
  }
}
// Unmount children that are no longer present.
for (name in prevChildren) {
  if (prevChildren.hasOwnProperty(name) && !(nextChildren && nextChildren.hasOwnProperty(name))) {
    prevChild = prevChildren[name];
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype.moveChild"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>moveChild (child, afterNode, toIndex, lastIndex)](#apidoc.element.react-dom.ReactDOMComponent.prototype.moveChild)
- description and source-code
```javascript
moveChild = function (child, afterNode, toIndex, lastIndex) {
  // If the index of 'child' is less than 'lastIndex', then it needs to
  // be moved. Otherwise, we do not need to move it because a child will be
  // inserted or moved before 'child'.
  if (child._mountIndex < lastIndex) {
    return makeMove(child, afterNode, toIndex);
  }
}
```
- example usage
```shell
...
      for (name in nextChildren) {
if (!nextChildren.hasOwnProperty(name)) {
  continue;
}
var prevChild = prevChildren && prevChildren[name];
var nextChild = nextChildren[name];
if (prevChild === nextChild) {
  updates = enqueue(updates, this.moveChild(prevChild, lastPlacedNode, nextIndex, lastIndex));
  lastIndex = Math.max(prevChild._mountIndex, lastIndex);
  prevChild._mountIndex = nextIndex;
} else {
  if (prevChild) {
    // Update 'lastIndex' before '_mountIndex' gets unset by unmounting.
    lastIndex = Math.max(prevChild._mountIndex, lastIndex);
    // The 'removedNodes' loop below will actually remove the child.
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype.receiveComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>receiveComponent (nextElement, transaction, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype.receiveComponent)
- description and source-code
```javascript
receiveComponent = function (nextElement, transaction, context) {
  var prevElement = this._currentElement;
  this._currentElement = nextElement;
  this.updateComponent(transaction, prevElement, nextElement, context);
}
```
- example usage
```shell
...
if (!nextChildren.hasOwnProperty(name)) {
  continue;
}
prevChild = prevChildren && prevChildren[name];
var prevElement = prevChild && prevChild._currentElement;
var nextElement = nextChildren[name];
if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
  ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
  nextChildren[name] = prevChild;
} else {
  if (prevChild) {
    removedNodes[name] = ReactReconciler.getHostNode(prevChild);
    ReactReconciler.unmountComponent(prevChild, false);
  }
  // The child must be instantiated before it's mounted.
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype.removeChild"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>removeChild (child, node)](#apidoc.element.react-dom.ReactDOMComponent.prototype.removeChild)
- description and source-code
```javascript
removeChild = function (child, node) {
  return makeRemove(child, node);
}
```
- example usage
```shell
...
}

function removeChild(parentNode, childNode) {
if (Array.isArray(childNode)) {
  var closingComment = childNode[1];
  childNode = childNode[0];
  removeDelimitedText(parentNode, childNode, closingComment);
  parentNode.removeChild(closingComment);
}
parentNode.removeChild(childNode);
}

function moveDelimitedText(parentNode, openingComment, closingComment, referenceNode) {
var node = openingComment;
while (true) {
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype.unmountChildren"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>unmountChildren (safely)](#apidoc.element.react-dom.ReactDOMComponent.prototype.unmountChildren)
- description and source-code
```javascript
unmountChildren = function (safely) {
  var renderedChildren = this._renderedChildren;
  ReactChildReconciler.unmountChildren(renderedChildren, safely);
  this._renderedChildren = null;
}
```
- example usage
```shell
...
     * take advantage of React's reconciliation for styling and <title>
     * management. So we just document it and throw in dangerous cases.
     */
    !false ? process.env.NODE_ENV !== 'production' ? invariant(false, '<%s> tried to unmount. Because of cross-browser quirks it
 is impossible to unmount some top-level components (eg <html>, <head>, and <body>) reliably and efficiently. To fix this, have
a single top-level component that never unmounts render these elements.', this._tag) : _prodInvariant('66', this._tag) : void 0;
    break;
}

this.unmountChildren(safely);
ReactDOMComponentTree.uncacheNode(this);
EventPluginHub.deleteAllListeners(this);
this._rootNodeID = 0;
this._domID = 0;
this._wrapperState = null;

if (process.env.NODE_ENV !== 'production') {
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype.unmountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>unmountComponent (safely)](#apidoc.element.react-dom.ReactDOMComponent.prototype.unmountComponent)
- description and source-code
```javascript
unmountComponent = function (safely) {
  switch (this._tag) {
    case 'audio':
    case 'form':
    case 'iframe':
    case 'img':
    case 'link':
    case 'object':
    case 'source':
    case 'video':
      var listeners = this._wrapperState.listeners;
      if (listeners) {
        for (var i = 0; i < listeners.length; i++) {
          listeners[i].remove();
        }
      }
      break;
    case 'html':
    case 'head':
    case 'body':
<span class="apidocCodeCommentSpan">      /**
       * Components like <html> <head> and <body> can't be removed or added
       * easily in a cross-browser way, however it's valuable to be able to
       * take advantage of React's reconciliation for styling and <title>
       * management. So we just document it and throw in dangerous cases.
       */
</span>      !false ? process.env.NODE_ENV !== 'production' ? invariant(false, '<%s> tried to unmount. Because of cross-browser quirks
it is impossible to unmount some top-level components (eg <html>, <head>, and <body>) reliably and efficiently. To fix this, have
 a single top-level component that never unmounts render these elements.', this._tag) : _prodInvariant('66', this._tag) : void 0
;
      break;
  }

  this.unmountChildren(safely);
  ReactDOMComponentTree.uncacheNode(this);
  EventPluginHub.deleteAllListeners(this);
  this._rootNodeID = 0;
  this._domID = 0;
  this._wrapperState = null;

  if (process.env.NODE_ENV !== 'production') {
    setAndValidateContentChildDev.call(this, null);
  }
}
```
- example usage
```shell
...
var nextElement = nextChildren[name];
if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
  ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
  nextChildren[name] = prevChild;
} else {
  if (prevChild) {
    removedNodes[name] = ReactReconciler.getHostNode(prevChild);
    ReactReconciler.unmountComponent(prevChild, false);
  }
  // The child must be instantiated before it's mounted.
  var nextChildInstance = instantiateReactComponent(nextElement, true);
  nextChildren[name] = nextChildInstance;
  // Creating mount image now ensures refs are resolved in right order
  // (see https://github.com/facebook/react/pull/7101 for explanation).
  var nextChildMountImage = ReactReconciler.mountComponent(nextChildInstance, transaction, hostParent, hostContainerInfo, context
, selfDebugID);
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype.updateChildren"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>updateChildren (nextNestedChildrenElements, transaction, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype.updateChildren)
- description and source-code
```javascript
updateChildren = function (nextNestedChildrenElements, transaction, context) {
  // Hook used by React ART
  this._updateChildren(nextNestedChildrenElements, transaction, context);
}
```
- example usage
```shell
...
var nextChildren = nextContent != null ? null : nextProps.children;

// If we're switching from children to content/html or vice versa, remove
// the old content
var lastHasContentOrHtml = lastContent != null || lastHtml != null;
var nextHasContentOrHtml = nextContent != null || nextHtml != null;
if (lastChildren != null && nextChildren == null) {
  this.updateChildren(null, transaction, context);
} else if (lastHasContentOrHtml && !nextHasContentOrHtml) {
  this.updateTextContent('');
  if (process.env.NODE_ENV !== 'production') {
    ReactInstrumentation.debugTool.onSetChildren(this._debugID, []);
  }
}
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype.updateComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>updateComponent (transaction, prevElement, nextElement, context)](#apidoc.element.react-dom.ReactDOMComponent.prototype.updateComponent)
- description and source-code
```javascript
updateComponent = function (transaction, prevElement, nextElement, context) {
  var lastProps = prevElement.props;
  var nextProps = this._currentElement.props;

  switch (this._tag) {
    case 'input':
      lastProps = ReactDOMInput.getHostProps(this, lastProps);
      nextProps = ReactDOMInput.getHostProps(this, nextProps);
      break;
    case 'option':
      lastProps = ReactDOMOption.getHostProps(this, lastProps);
      nextProps = ReactDOMOption.getHostProps(this, nextProps);
      break;
    case 'select':
      lastProps = ReactDOMSelect.getHostProps(this, lastProps);
      nextProps = ReactDOMSelect.getHostProps(this, nextProps);
      break;
    case 'textarea':
      lastProps = ReactDOMTextarea.getHostProps(this, lastProps);
      nextProps = ReactDOMTextarea.getHostProps(this, nextProps);
      break;
  }

  assertValidProps(this, nextProps);
  this._updateDOMProperties(lastProps, nextProps, transaction);
  this._updateDOMChildren(lastProps, nextProps, transaction, context);

  switch (this._tag) {
    case 'input':
      // Update the wrapper around inputs *after* updating props. This has to
      // happen after '_updateDOMProperties'. Otherwise HTML5 input validations
      // raise warnings and prevent the new value from being assigned.
      ReactDOMInput.updateWrapper(this);
      break;
    case 'textarea':
      ReactDOMTextarea.updateWrapper(this);
      break;
    case 'select':
      // <select> value update needs to occur after <option> children
      // reconciliation
      transaction.getReactMountReady().enqueue(postUpdateSelectWrapper, this);
      break;
  }
}
```
- example usage
```shell
...

receiveComponent: function (nextElement, transaction, nextContext) {
  var prevElement = this._currentElement;
  var prevContext = this._context;

  this._pendingElement = null;

  this.updateComponent(transaction, prevElement, nextElement, prevContext, nextContext);
},

/**
 * If any of '_pendingElement', '_pendingStateQueue', or '_pendingForceUpdate'
 * is set, update the component.
 *
 * @param {ReactReconcileTransaction} transaction
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype.updateMarkup"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>updateMarkup (nextMarkup)](#apidoc.element.react-dom.ReactDOMComponent.prototype.updateMarkup)
- description and source-code
```javascript
updateMarkup = function (nextMarkup) {
  var prevChildren = this._renderedChildren;
  // Remove any rendered children.
  ReactChildReconciler.unmountChildren(prevChildren, false);
  for (var name in prevChildren) {
    if (prevChildren.hasOwnProperty(name)) {
      !false ? process.env.NODE_ENV !== 'production' ? invariant(false, 'updateTextContent called on non-empty component.') : _prodInvariant
('118') : void 0;
    }
  }
  var updates = [makeSetMarkup(nextMarkup)];
  processQueue(this, updates);
}
```
- example usage
```shell
...
    this.updateTextContent('' + nextContent);
    if (process.env.NODE_ENV !== 'production') {
      setAndValidateContentChildDev.call(this, nextContent);
    }
  }
} else if (nextHtml != null) {
  if (lastHtml !== nextHtml) {
    this.updateMarkup('' + nextHtml);
  }
  if (process.env.NODE_ENV !== 'production') {
    ReactInstrumentation.debugTool.onSetChildren(this._debugID, []);
  }
} else if (nextChildren != null) {
  if (process.env.NODE_ENV !== 'production') {
    setAndValidateContentChildDev.call(this, null);
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponent.prototype.updateTextContent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponent.prototype.</span>updateTextContent (nextContent)](#apidoc.element.react-dom.ReactDOMComponent.prototype.updateTextContent)
- description and source-code
```javascript
updateTextContent = function (nextContent) {
  var prevChildren = this._renderedChildren;
  // Remove any rendered children.
  ReactChildReconciler.unmountChildren(prevChildren, false);
  for (var name in prevChildren) {
    if (prevChildren.hasOwnProperty(name)) {
      !false ? process.env.NODE_ENV !== 'production' ? invariant(false, 'updateTextContent called on non-empty component.') : _prodInvariant
('118') : void 0;
    }
  }
  // Set new text content.
  var updates = [makeTextContent(nextContent)];
  processQueue(this, updates);
}
```
- example usage
```shell
...
// If we're switching from children to content/html or vice versa, remove
// the old content
var lastHasContentOrHtml = lastContent != null || lastHtml != null;
var nextHasContentOrHtml = nextContent != null || nextHtml != null;
if (lastChildren != null && nextChildren == null) {
  this.updateChildren(null, transaction, context);
} else if (lastHasContentOrHtml && !nextHasContentOrHtml) {
  this.updateTextContent('');
  if (process.env.NODE_ENV !== 'production') {
    ReactInstrumentation.debugTool.onSetChildren(this._debugID, []);
  }
}

if (nextContent != null) {
  if (lastContent !== nextContent) {
...
```



# <a name="apidoc.module.react-dom.ReactDOMComponentTree"></a>[module react-dom.ReactDOMComponentTree](#apidoc.module.react-dom.ReactDOMComponentTree)

#### <a name="apidoc.element.react-dom.ReactDOMComponentTree.getClosestInstanceFromNode"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponentTree.</span>getClosestInstanceFromNode (node)](#apidoc.element.react-dom.ReactDOMComponentTree.getClosestInstanceFromNode)
- description and source-code
```javascript
function getClosestInstanceFromNode(node) {
  if (node[internalInstanceKey]) {
    return node[internalInstanceKey];
  }

  // Walk up the tree until we find an ancestor whose instance we have cached.
  var parents = [];
  while (!node[internalInstanceKey]) {
    parents.push(node);
    if (node.parentNode) {
      node = node.parentNode;
    } else {
      // Top of the tree. This node must not be part of a React tree (or is
      // unmounted, potentially).
      return null;
    }
  }

  var closest;
  var inst;
  for (; node && (inst = node[internalInstanceKey]); node = parents.pop()) {
    closest = inst;
    if (parents.length) {
      precacheChildNodes(inst, node);
    }
  }

  return closest;
}
```
- example usage
```shell
...
}

var from;
var to;
if (topLevelType === 'topMouseOut') {
  from = targetInst;
  var related = nativeEvent.relatedTarget || nativeEvent.toElement;
  to = related ? ReactDOMComponentTree.getClosestInstanceFromNode(related) : null;
} else {
  // Moving to a node from outside the window.
  from = null;
  to = targetInst;
}

if (from === to) {
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponentTree.getInstanceFromNode"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponentTree.</span>getInstanceFromNode (node)](#apidoc.element.react-dom.ReactDOMComponentTree.getInstanceFromNode)
- description and source-code
```javascript
function getInstanceFromNode(node) {
  var inst = getClosestInstanceFromNode(node);
  if (inst != null && inst._hostNode === node) {
    return inst;
  } else {
    return null;
  }
}
```
- example usage
```shell
...
    } else {
      removeDelimitedText(parentNode, openingComment, closingComment);
    }
  }

  if (process.env.NODE_ENV !== 'production') {
    ReactInstrumentation.debugTool.onHostOperation({
      instanceID: ReactDOMComponentTree.getInstanceFromNode(openingComment)._debugID,
      type: 'replace text',
      payload: stringText
    });
  }
}

var dangerouslyReplaceNodeWithMarkup = Danger.dangerouslyReplaceNodeWithMarkup;
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponentTree.getNodeFromInstance"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponentTree.</span>getNodeFromInstance (inst)](#apidoc.element.react-dom.ReactDOMComponentTree.getNodeFromInstance)
- description and source-code
```javascript
function getNodeFromInstance(inst) {
  // Without this first invariant, passing a non-DOM-component triggers the next
  // invariant for a missing parent, which is super confusing.
  !(inst._hostNode !== undefined) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'getNodeFromInstance: Invalid argument
.') : _prodInvariant('33') : void 0;

  if (inst._hostNode) {
    return inst._hostNode;
  }

  // Walk up the tree until we find an ancestor whose DOM node we have cached.
  var parents = [];
  while (!inst._hostNode) {
    parents.push(inst);
    !inst._hostParent ? process.env.NODE_ENV !== 'production' ? invariant(false, 'React DOM tree root should always have a node
reference.') : _prodInvariant('34') : void 0;
    inst = inst._hostParent;
  }

  // Now parents contains each ancestor that does *not* have a cached native
  // node, and 'inst' is the deepest ancestor that does.
  for (; parents.length; inst = parents.pop()) {
    precacheChildNodes(inst, inst._hostNode);
  }

  return inst._hostNode;
}
```
- example usage
```shell
...

var ReactDOMComponentTree = require('./ReactDOMComponentTree');

var focusNode = require('fbjs/lib/focusNode');

var AutoFocusUtils = {
  focusDOMComponent: function () {
    focusNode(ReactDOMComponentTree.getNodeFromInstance(this));
  }
};

module.exports = AutoFocusUtils;
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponentTree.precacheChildNodes"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponentTree.</span>precacheChildNodes (inst, node)](#apidoc.element.react-dom.ReactDOMComponentTree.precacheChildNodes)
- description and source-code
```javascript
function precacheChildNodes(inst, node) {
  if (inst._flags & Flags.hasCachedChildNodes) {
    return;
  }
  var children = inst._renderedChildren;
  var childNode = node.firstChild;
  outer: for (var name in children) {
    if (!children.hasOwnProperty(name)) {
      continue;
    }
    var childInst = children[name];
    var childID = getRenderedHostOrTextFromComponent(childInst)._domID;
    if (childID === 0) {
      // We're currently unmounting this child in ReactMultiChild; skip it.
      continue;
    }
    // We assume the child nodes are in the same order as the child instances.
    for (; childNode !== null; childNode = childNode.nextSibling) {
      if (shouldPrecacheNode(childNode, childID)) {
        precacheNode(childInst, childNode);
        continue outer;
      }
    }
    // We reached the end of the DOM children without finding an ID match.
    !false ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Unable to find element with ID %s.', childID) : _prodInvariant
('32', childID) : void 0;
  }
  inst._flags |= Flags.hasCachedChildNodes;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactDOMComponentTree.precacheNode"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponentTree.</span>precacheNode (inst, node)](#apidoc.element.react-dom.ReactDOMComponentTree.precacheNode)
- description and source-code
```javascript
function precacheNode(inst, node) {
  var hostInst = getRenderedHostOrTextFromComponent(inst);
  hostInst._hostNode = node;
  node[internalInstanceKey] = hostInst;
}
```
- example usage
```shell
...
    // See discussion in https://github.com/facebook/react/pull/6896
    // and discussion in https://bugzilla.mozilla.org/show_bug.cgi?id=1276240
    el = ownerDocument.createElement(this._currentElement.type);
  }
} else {
  el = ownerDocument.createElementNS(namespaceURI, this._currentElement.type);
}
ReactDOMComponentTree.precacheNode(this, el);
this._flags |= Flags.hasCachedChildNodes;
if (!this._hostParent) {
  DOMPropertyOperations.setAttributeForRoot(el);
}
this._updateDOMProperties(null, props, transaction);
var lazyTree = DOMLazyTree(el);
this._createInitialChildren(transaction, props, context, lazyTree);
...
```

#### <a name="apidoc.element.react-dom.ReactDOMComponentTree.uncacheNode"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMComponentTree.</span>uncacheNode (inst)](#apidoc.element.react-dom.ReactDOMComponentTree.uncacheNode)
- description and source-code
```javascript
function uncacheNode(inst) {
  var node = inst._hostNode;
  if (node) {
    delete node[internalInstanceKey];
    inst._hostNode = null;
  }
}
```
- example usage
```shell
...
     * management. So we just document it and throw in dangerous cases.
     */
    !false ? process.env.NODE_ENV !== 'production' ? invariant(false, '<%s> tried to unmount. Because of cross-browser quirks it
 is impossible to unmount some top-level components (eg <html>, <head>, and <body>) reliably and efficiently. To fix this, have
a single top-level component that never unmounts render these elements.', this._tag) : _prodInvariant('66', this._tag) : void 0;
    break;
}

this.unmountChildren(safely);
ReactDOMComponentTree.uncacheNode(this);
EventPluginHub.deleteAllListeners(this);
this._rootNodeID = 0;
this._domID = 0;
this._wrapperState = null;

if (process.env.NODE_ENV !== 'production') {
  setAndValidateContentChildDev.call(this, null);
...
```



# <a name="apidoc.module.react-dom.ReactDOMEmptyComponent"></a>[module react-dom.ReactDOMEmptyComponent](#apidoc.module.react-dom.ReactDOMEmptyComponent)

#### <a name="apidoc.element.react-dom.ReactDOMEmptyComponent.ReactDOMEmptyComponent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ReactDOMEmptyComponent (instantiate)](#apidoc.element.react-dom.ReactDOMEmptyComponent.ReactDOMEmptyComponent)
- description and source-code
```javascript
ReactDOMEmptyComponent = function (instantiate) {
  // ReactCompositeComponent uses this:
  this._currentElement = null;
  // ReactDOMComponentTree uses these:
  this._hostNode = null;
  this._hostParent = null;
  this._hostContainerInfo = null;
  this._domID = 0;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactDOMEmptyComponent.prototype"></a>[module react-dom.ReactDOMEmptyComponent.prototype](#apidoc.module.react-dom.ReactDOMEmptyComponent.prototype)

#### <a name="apidoc.element.react-dom.ReactDOMEmptyComponent.prototype.getHostNode"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMEmptyComponent.prototype.</span>getHostNode ()](#apidoc.element.react-dom.ReactDOMEmptyComponent.prototype.getHostNode)
- description and source-code
```javascript
getHostNode = function () {
  return ReactDOMComponentTree.getNodeFromInstance(this);
}
```
- example usage
```shell
...
var prevElement = prevChild && prevChild._currentElement;
var nextElement = nextChildren[name];
if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
  ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
  nextChildren[name] = prevChild;
} else {
  if (prevChild) {
    removedNodes[name] = ReactReconciler.getHostNode(prevChild);
    ReactReconciler.unmountComponent(prevChild, false);
  }
  // The child must be instantiated before it's mounted.
  var nextChildInstance = instantiateReactComponent(nextElement, true);
  nextChildren[name] = nextChildInstance;
  // Creating mount image now ensures refs are resolved in right order
  // (see https://github.com/facebook/react/pull/7101 for explanation).
...
```

#### <a name="apidoc.element.react-dom.ReactDOMEmptyComponent.prototype.mountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMEmptyComponent.prototype.</span>mountComponent (transaction, hostParent, hostContainerInfo, context)](#apidoc.element.react-dom.ReactDOMEmptyComponent.prototype.mountComponent)
- description and source-code
```javascript
mountComponent = function (transaction, hostParent, hostContainerInfo, context) {
  var domID = hostContainerInfo._idCounter++;
  this._domID = domID;
  this._hostParent = hostParent;
  this._hostContainerInfo = hostContainerInfo;

  var nodeValue = ' react-empty: ' + this._domID + ' ';
  if (transaction.useCreateElement) {
    var ownerDocument = hostContainerInfo._ownerDocument;
    var node = ownerDocument.createComment(nodeValue);
    ReactDOMComponentTree.precacheNode(this, node);
    return DOMLazyTree(node);
  } else {
    if (transaction.renderToStaticMarkup) {
      // Normally we'd insert a comment node, but since this is a situation
      // where React won't take over (static pages), we can simply return
      // nothing.
      return '';
    }
    return '<!--' + nodeValue + '-->';
  }
}
```
- example usage
```shell
...
      ReactReconciler.unmountComponent(prevChild, false);
    }
    // The child must be instantiated before it's mounted.
    var nextChildInstance = instantiateReactComponent(nextElement, true);
    nextChildren[name] = nextChildInstance;
    // Creating mount image now ensures refs are resolved in right order
    // (see https://github.com/facebook/react/pull/7101 for explanation).
    var nextChildMountImage = ReactReconciler.mountComponent(nextChildInstance, transaction, hostParent, hostContainerInfo, context
, selfDebugID);
    mountImages.push(nextChildMountImage);
  }
}
// Unmount children that are no longer present.
for (name in prevChildren) {
  if (prevChildren.hasOwnProperty(name) && !(nextChildren && nextChildren.hasOwnProperty(name))) {
    prevChild = prevChildren[name];
...
```

#### <a name="apidoc.element.react-dom.ReactDOMEmptyComponent.prototype.receiveComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMEmptyComponent.prototype.</span>receiveComponent ()](#apidoc.element.react-dom.ReactDOMEmptyComponent.prototype.receiveComponent)
- description and source-code
```javascript
receiveComponent = function () {}
```
- example usage
```shell
...
if (!nextChildren.hasOwnProperty(name)) {
  continue;
}
prevChild = prevChildren && prevChildren[name];
var prevElement = prevChild && prevChild._currentElement;
var nextElement = nextChildren[name];
if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
  ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
  nextChildren[name] = prevChild;
} else {
  if (prevChild) {
    removedNodes[name] = ReactReconciler.getHostNode(prevChild);
    ReactReconciler.unmountComponent(prevChild, false);
  }
  // The child must be instantiated before it's mounted.
...
```

#### <a name="apidoc.element.react-dom.ReactDOMEmptyComponent.prototype.unmountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMEmptyComponent.prototype.</span>unmountComponent ()](#apidoc.element.react-dom.ReactDOMEmptyComponent.prototype.unmountComponent)
- description and source-code
```javascript
unmountComponent = function () {
  ReactDOMComponentTree.uncacheNode(this);
}
```
- example usage
```shell
...
var nextElement = nextChildren[name];
if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
  ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
  nextChildren[name] = prevChild;
} else {
  if (prevChild) {
    removedNodes[name] = ReactReconciler.getHostNode(prevChild);
    ReactReconciler.unmountComponent(prevChild, false);
  }
  // The child must be instantiated before it's mounted.
  var nextChildInstance = instantiateReactComponent(nextElement, true);
  nextChildren[name] = nextChildInstance;
  // Creating mount image now ensures refs are resolved in right order
  // (see https://github.com/facebook/react/pull/7101 for explanation).
  var nextChildMountImage = ReactReconciler.mountComponent(nextChildInstance, transaction, hostParent, hostContainerInfo, context
, selfDebugID);
...
```



# <a name="apidoc.module.react-dom.ReactDOMIDOperations"></a>[module react-dom.ReactDOMIDOperations](#apidoc.module.react-dom.ReactDOMIDOperations)

#### <a name="apidoc.element.react-dom.ReactDOMIDOperations.dangerouslyProcessChildrenUpdates"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMIDOperations.</span>dangerouslyProcessChildrenUpdates (parentInst, updates)](#apidoc.element.react-dom.ReactDOMIDOperations.dangerouslyProcessChildrenUpdates)
- description and source-code
```javascript
dangerouslyProcessChildrenUpdates = function (parentInst, updates) {
  var node = ReactDOMComponentTree.getNodeFromInstance(parentInst);
  DOMChildrenOperations.processUpdates(node, updates);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactDOMInput"></a>[module react-dom.ReactDOMInput](#apidoc.module.react-dom.ReactDOMInput)

#### <a name="apidoc.element.react-dom.ReactDOMInput.getHostProps"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMInput.</span>getHostProps (inst, props)](#apidoc.element.react-dom.ReactDOMInput.getHostProps)
- description and source-code
```javascript
getHostProps = function (inst, props) {
  var value = LinkedValueUtils.getValue(props);
  var checked = LinkedValueUtils.getChecked(props);

  var hostProps = _assign({
    // Make sure we set .type before any other properties (setting .value
    // before .type means .value is lost in IE11 and below)
    type: undefined,
    // Make sure we set .step before .value (setting .value before .step
    // means .value is rounded on mount, based upon step precision)
    step: undefined,
    // Make sure we set .min & .max before .value (to ensure proper order
    // in corner cases such as min or max deriving from value, e.g. Issue #7170)
    min: undefined,
    max: undefined
  }, props, {
    defaultChecked: undefined,
    defaultValue: undefined,
    value: value != null ? value : inst._wrapperState.initialValue,
    checked: checked != null ? checked : inst._wrapperState.initialChecked,
    onChange: inst._wrapperState.onChange
  });

  return hostProps;
}
```
- example usage
```shell
...
  this._wrapperState = {
    listeners: null
  };
  transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
  break;
case 'input':
  ReactDOMInput.mountWrapper(this, props, hostParent);
  props = ReactDOMInput.getHostProps(this, props);
  transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
  break;
case 'option':
  ReactDOMOption.mountWrapper(this, props, hostParent);
  props = ReactDOMOption.getHostProps(this, props);
  break;
case 'select':
...
```

#### <a name="apidoc.element.react-dom.ReactDOMInput.mountWrapper"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMInput.</span>mountWrapper (inst, props)](#apidoc.element.react-dom.ReactDOMInput.mountWrapper)
- description and source-code
```javascript
mountWrapper = function (inst, props) {
  if (process.env.NODE_ENV !== 'production') {
    LinkedValueUtils.checkPropTypes('input', props, inst._currentElement._owner);

    var owner = inst._currentElement._owner;

    if (props.valueLink !== undefined && !didWarnValueLink) {
      process.env.NODE_ENV !== 'production' ? warning(false, ''valueLink' prop on 'input' is deprecated; set 'value' and 'onChange
' instead.') : void 0;
      didWarnValueLink = true;
    }
    if (props.checkedLink !== undefined && !didWarnCheckedLink) {
      process.env.NODE_ENV !== 'production' ? warning(false, ''checkedLink' prop on 'input' is deprecated; set 'value' and 'onChange
' instead.') : void 0;
      didWarnCheckedLink = true;
    }
    if (props.checked !== undefined && props.defaultChecked !== undefined && !didWarnCheckedDefaultChecked) {
      process.env.NODE_ENV !== 'production' ? warning(false, '%s contains an input of type %s with both checked and defaultChecked
 props. ' + 'Input elements must be either controlled or uncontrolled ' + '(specify either the checked prop, or the defaultChecked
 prop, but not ' + 'both). Decide between using a controlled or uncontrolled input ' + 'element and remove one of these props. More
 info: ' + 'https://fb.me/react-controlled-components', owner && owner.getName() || 'A component', props.type) : void 0;
      didWarnCheckedDefaultChecked = true;
    }
    if (props.value !== undefined && props.defaultValue !== undefined && !didWarnValueDefaultValue) {
      process.env.NODE_ENV !== 'production' ? warning(false, '%s contains an input of type %s with both value and defaultValue props
. ' + 'Input elements must be either controlled or uncontrolled ' + '(specify either the value prop, or the defaultValue prop, but
 not ' + 'both). Decide between using a controlled or uncontrolled input ' + 'element and remove one of these props. More info: ' + '
https://fb.me/react-controlled-components', owner && owner.getName() || 'A component', props.type) : void 0;
      didWarnValueDefaultValue = true;
    }
  }

  var defaultValue = props.defaultValue;
  inst._wrapperState = {
    initialChecked: props.checked != null ? props.checked : props.defaultChecked,
    initialValue: props.value != null ? props.value : defaultValue,
    listeners: null,
    onChange: _handleChange.bind(inst),
    controlled: isControlled(props)
  };
}
```
- example usage
```shell
...
case 'video':
  this._wrapperState = {
    listeners: null
  };
  transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
  break;
case 'input':
  ReactDOMInput.mountWrapper(this, props, hostParent);
  props = ReactDOMInput.getHostProps(this, props);
  transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
  break;
case 'option':
  ReactDOMOption.mountWrapper(this, props, hostParent);
  props = ReactDOMOption.getHostProps(this, props);
  break;
...
```

#### <a name="apidoc.element.react-dom.ReactDOMInput.postMountWrapper"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMInput.</span>postMountWrapper (inst)](#apidoc.element.react-dom.ReactDOMInput.postMountWrapper)
- description and source-code
```javascript
postMountWrapper = function (inst) {
  var props = inst._currentElement.props;

  // This is in postMount because we need access to the DOM node, which is not
  // available until after the component has mounted.
  var node = ReactDOMComponentTree.getNodeFromInstance(inst);

  // Detach value from defaultValue. We won't do anything if we're working on
  // submit or reset inputs as those values & defaultValues are linked. They
  // are not resetable nodes so this operation doesn't matter and actually
  // removes browser-default values (eg "Submit Query") when no value is
  // provided.

  switch (props.type) {
    case 'submit':
    case 'reset':
      break;
    case 'color':
    case 'date':
    case 'datetime':
    case 'datetime-local':
    case 'month':
    case 'time':
    case 'week':
      // This fixes the no-show issue on iOS Safari and Android Chrome:
      // https://github.com/facebook/react/issues/7233
      node.value = '';
      node.value = node.defaultValue;
      break;
    default:
      node.value = node.value;
      break;
  }

  // Normally, we'd just do 'node.checked = node.checked' upon initial mount, less this bug
  // this is needed to work around a chrome bug where setting defaultChecked
  // will sometimes influence the value of checked (even after detachment).
  // Reference: https://bugs.chromium.org/p/chromium/issues/detail?id=608416
  // We need to temporarily unset name to avoid disrupting radio button groups.
  var name = node.name;
  if (name !== '') {
    node.name = '';
  }
  node.defaultChecked = !node.defaultChecked;
  node.defaultChecked = !node.defaultChecked;
  if (name !== '') {
    node.name = name;
  }
}
```
- example usage
```shell
...
function putListener() {
  var listenerToPut = this;
  EventPluginHub.putListener(listenerToPut.inst, listenerToPut.registrationName, listenerToPut.listener);
}

function inputPostMount() {
  var inst = this;
  ReactDOMInput.postMountWrapper(inst);
}

function textareaPostMount() {
  var inst = this;
  ReactDOMTextarea.postMountWrapper(inst);
}
...
```

#### <a name="apidoc.element.react-dom.ReactDOMInput.updateWrapper"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMInput.</span>updateWrapper (inst)](#apidoc.element.react-dom.ReactDOMInput.updateWrapper)
- description and source-code
```javascript
updateWrapper = function (inst) {
  var props = inst._currentElement.props;

  if (process.env.NODE_ENV !== 'production') {
    var controlled = isControlled(props);
    var owner = inst._currentElement._owner;

    if (!inst._wrapperState.controlled && controlled && !didWarnUncontrolledToControlled) {
      process.env.NODE_ENV !== 'production' ? warning(false, '%s is changing an uncontrolled input of type %s to be controlled. ' + '
Input elements should not switch from uncontrolled to controlled (or vice versa). ' + 'Decide between using a controlled or uncontrolled
 input ' + 'element for the lifetime of the component. More info: https://fb.me/react-controlled-components', owner && owner.getName
() || 'A component', props.type) : void 0;
      didWarnUncontrolledToControlled = true;
    }
    if (inst._wrapperState.controlled && !controlled && !didWarnControlledToUncontrolled) {
      process.env.NODE_ENV !== 'production' ? warning(false, '%s is changing a controlled input of type %s to be uncontrolled. ' + '
Input elements should not switch from controlled to uncontrolled (or vice versa). ' + 'Decide between using a controlled or uncontrolled
 input ' + 'element for the lifetime of the component. More info: https://fb.me/react-controlled-components', owner && owner.getName
() || 'A component', props.type) : void 0;
      didWarnControlledToUncontrolled = true;
    }
  }

  // TODO: Shouldn't this be getChecked(props)?
  var checked = props.checked;
  if (checked != null) {
    DOMPropertyOperations.setValueForProperty(ReactDOMComponentTree.getNodeFromInstance(inst), 'checked', checked || false);
  }

  var node = ReactDOMComponentTree.getNodeFromInstance(inst);
  var value = LinkedValueUtils.getValue(props);
  if (value != null) {
    if (value === 0 && node.value === '') {
      node.value = '0';
      // Note: IE9 reports a number inputs as 'text', so check props instead.
    } else if (props.type === 'number') {
      // Simulate 'input.valueAsNumber'. IE9 does not support it
      var valueAsNumber = parseFloat(node.value, 10) || 0;

      // eslint-disable-next-line
      if (value != valueAsNumber) {
        // Cast 'value' to a string to ensure the value is set correctly. While
        // browsers typically do this as necessary, jsdom doesn't.
        node.value = '' + value;
      }
      // eslint-disable-next-line
    } else if (value != node.value) {
      // Cast 'value' to a string to ensure the value is set correctly. While
      // browsers typically do this as necessary, jsdom doesn't.
      node.value = '' + value;
    }
  } else {
    if (props.value == null && props.defaultValue != null) {
      // In Chrome, assigning defaultValue to certain input types triggers input validation.
      // For number inputs, the display value loses trailing decimal points. For email inputs,
      // Chrome raises "The specified value <x> is not a valid email address".
      //
      // Here we check to see if the defaultValue has actually changed, avoiding these problems
      // when the user is inputting text
      //
      // https://github.com/facebook/react/issues/7253
      if (node.defaultValue !== '' + props.defaultValue) {
        node.defaultValue = '' + props.defaultValue;
      }
    }
    if (props.checked == null && props.defaultChecked != null) {
      node.defaultChecked = !!props.defaultChecked;
    }
  }
}
```
- example usage
```shell
...
this._updateDOMChildren(lastProps, nextProps, transaction, context);

switch (this._tag) {
  case 'input':
    // Update the wrapper around inputs *after* updating props. This has to
    // happen after '_updateDOMProperties'. Otherwise HTML5 input validations
    // raise warnings and prevent the new value from being assigned.
    ReactDOMInput.updateWrapper(this);
    break;
  case 'textarea':
    ReactDOMTextarea.updateWrapper(this);
    break;
  case 'select':
    // <select> value update needs to occur after <option> children
    // reconciliation
...
```



# <a name="apidoc.module.react-dom.ReactDOMInvalidARIAHook"></a>[module react-dom.ReactDOMInvalidARIAHook](#apidoc.module.react-dom.ReactDOMInvalidARIAHook)

#### <a name="apidoc.element.react-dom.ReactDOMInvalidARIAHook.onBeforeMountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMInvalidARIAHook.</span>onBeforeMountComponent (debugID, element)](#apidoc.element.react-dom.ReactDOMInvalidARIAHook.onBeforeMountComponent)
- description and source-code
```javascript
onBeforeMountComponent = function (debugID, element) {
  if (process.env.NODE_ENV !== 'production') {
    handleElement(debugID, element);
  }
}
```
- example usage
```shell
...

    validateDOMNesting(null, String(content), this, this._ancestorInfo);
    this._contentDebugID = contentDebugID;
    if (hasExistingContent) {
      ReactInstrumentation.debugTool.onBeforeUpdateComponent(contentDebugID, content);
      ReactInstrumentation.debugTool.onUpdateComponent(contentDebugID);
    } else {
      ReactInstrumentation.debugTool.onBeforeMountComponent(contentDebugID, content, debugID);
      ReactInstrumentation.debugTool.onMountComponent(contentDebugID);
      ReactInstrumentation.debugTool.onSetChildren(debugID, [contentDebugID]);
    }
  };
}

// There are so many media events, it makes sense to just
...
```

#### <a name="apidoc.element.react-dom.ReactDOMInvalidARIAHook.onBeforeUpdateComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMInvalidARIAHook.</span>onBeforeUpdateComponent (debugID, element)](#apidoc.element.react-dom.ReactDOMInvalidARIAHook.onBeforeUpdateComponent)
- description and source-code
```javascript
onBeforeUpdateComponent = function (debugID, element) {
  if (process.env.NODE_ENV !== 'production') {
    handleElement(debugID, element);
  }
}
```
- example usage
```shell
...
    this._contentDebugID = null;
    return;
  }

  validateDOMNesting(null, String(content), this, this._ancestorInfo);
  this._contentDebugID = contentDebugID;
  if (hasExistingContent) {
    ReactInstrumentation.debugTool.onBeforeUpdateComponent(contentDebugID, content);
    ReactInstrumentation.debugTool.onUpdateComponent(contentDebugID);
  } else {
    ReactInstrumentation.debugTool.onBeforeMountComponent(contentDebugID, content, debugID);
    ReactInstrumentation.debugTool.onMountComponent(contentDebugID);
    ReactInstrumentation.debugTool.onSetChildren(debugID, [contentDebugID]);
  }
};
...
```



# <a name="apidoc.module.react-dom.ReactDOMNullInputValuePropHook"></a>[module react-dom.ReactDOMNullInputValuePropHook](#apidoc.module.react-dom.ReactDOMNullInputValuePropHook)

#### <a name="apidoc.element.react-dom.ReactDOMNullInputValuePropHook.onBeforeMountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMNullInputValuePropHook.</span>onBeforeMountComponent (debugID, element)](#apidoc.element.react-dom.ReactDOMNullInputValuePropHook.onBeforeMountComponent)
- description and source-code
```javascript
onBeforeMountComponent = function (debugID, element) {
  handleElement(debugID, element);
}
```
- example usage
```shell
...

    validateDOMNesting(null, String(content), this, this._ancestorInfo);
    this._contentDebugID = contentDebugID;
    if (hasExistingContent) {
      ReactInstrumentation.debugTool.onBeforeUpdateComponent(contentDebugID, content);
      ReactInstrumentation.debugTool.onUpdateComponent(contentDebugID);
    } else {
      ReactInstrumentation.debugTool.onBeforeMountComponent(contentDebugID, content, debugID);
      ReactInstrumentation.debugTool.onMountComponent(contentDebugID);
      ReactInstrumentation.debugTool.onSetChildren(debugID, [contentDebugID]);
    }
  };
}

// There are so many media events, it makes sense to just
...
```

#### <a name="apidoc.element.react-dom.ReactDOMNullInputValuePropHook.onBeforeUpdateComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMNullInputValuePropHook.</span>onBeforeUpdateComponent (debugID, element)](#apidoc.element.react-dom.ReactDOMNullInputValuePropHook.onBeforeUpdateComponent)
- description and source-code
```javascript
onBeforeUpdateComponent = function (debugID, element) {
  handleElement(debugID, element);
}
```
- example usage
```shell
...
    this._contentDebugID = null;
    return;
  }

  validateDOMNesting(null, String(content), this, this._ancestorInfo);
  this._contentDebugID = contentDebugID;
  if (hasExistingContent) {
    ReactInstrumentation.debugTool.onBeforeUpdateComponent(contentDebugID, content);
    ReactInstrumentation.debugTool.onUpdateComponent(contentDebugID);
  } else {
    ReactInstrumentation.debugTool.onBeforeMountComponent(contentDebugID, content, debugID);
    ReactInstrumentation.debugTool.onMountComponent(contentDebugID);
    ReactInstrumentation.debugTool.onSetChildren(debugID, [contentDebugID]);
  }
};
...
```



# <a name="apidoc.module.react-dom.ReactDOMOption"></a>[module react-dom.ReactDOMOption](#apidoc.module.react-dom.ReactDOMOption)

#### <a name="apidoc.element.react-dom.ReactDOMOption.getHostProps"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMOption.</span>getHostProps (inst, props)](#apidoc.element.react-dom.ReactDOMOption.getHostProps)
- description and source-code
```javascript
getHostProps = function (inst, props) {
  var hostProps = _assign({ selected: undefined, children: undefined }, props);

  // Read state only from initial mount because <select> updates value
  // manually; we need the initial state only for server rendering
  if (inst._wrapperState.selected != null) {
    hostProps.selected = inst._wrapperState.selected;
  }

  var content = flattenChildren(props.children);

  if (content) {
    hostProps.children = content;
  }

  return hostProps;
}
```
- example usage
```shell
...
  this._wrapperState = {
    listeners: null
  };
  transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
  break;
case 'input':
  ReactDOMInput.mountWrapper(this, props, hostParent);
  props = ReactDOMInput.getHostProps(this, props);
  transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
  break;
case 'option':
  ReactDOMOption.mountWrapper(this, props, hostParent);
  props = ReactDOMOption.getHostProps(this, props);
  break;
case 'select':
...
```

#### <a name="apidoc.element.react-dom.ReactDOMOption.mountWrapper"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMOption.</span>mountWrapper (inst, props, hostParent)](#apidoc.element.react-dom.ReactDOMOption.mountWrapper)
- description and source-code
```javascript
mountWrapper = function (inst, props, hostParent) {
  // TODO (yungsters): Remove support for 'selected' in <option>.
  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(props.selected == null, 'Use the 'defaultValue' or 'value' props on <select>
instead of ' + 'setting 'selected' on <option>.') : void 0;
  }

  // Look up whether this option is 'selected'
  var selectValue = null;
  if (hostParent != null) {
    var selectParent = hostParent;

    if (selectParent._tag === 'optgroup') {
      selectParent = selectParent._hostParent;
    }

    if (selectParent != null && selectParent._tag === 'select') {
      selectValue = ReactDOMSelect.getSelectValueContext(selectParent);
    }
  }

  // If the value is null (e.g., no specified value or after initial mount)
  // or missing (e.g., for <datalist>), we don't change props.selected
  var selected = null;
  if (selectValue != null) {
    var value;
    if (props.value != null) {
      value = props.value + '';
    } else {
      value = flattenChildren(props.children);
    }
    selected = false;
    if (Array.isArray(selectValue)) {
      // multiple
      for (var i = 0; i < selectValue.length; i++) {
        if ('' + selectValue[i] === value) {
          selected = true;
          break;
        }
      }
    } else {
      selected = '' + selectValue === value;
    }
  }

  inst._wrapperState = { selected: selected };
}
```
- example usage
```shell
...
case 'video':
  this._wrapperState = {
    listeners: null
  };
  transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
  break;
case 'input':
  ReactDOMInput.mountWrapper(this, props, hostParent);
  props = ReactDOMInput.getHostProps(this, props);
  transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
  break;
case 'option':
  ReactDOMOption.mountWrapper(this, props, hostParent);
  props = ReactDOMOption.getHostProps(this, props);
  break;
...
```

#### <a name="apidoc.element.react-dom.ReactDOMOption.postMountWrapper"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMOption.</span>postMountWrapper (inst)](#apidoc.element.react-dom.ReactDOMOption.postMountWrapper)
- description and source-code
```javascript
postMountWrapper = function (inst) {
  // value="" should make a value attribute (#6219)
  var props = inst._currentElement.props;
  if (props.value != null) {
    var node = ReactDOMComponentTree.getNodeFromInstance(inst);
    node.setAttribute('value', props.value);
  }
}
```
- example usage
```shell
...
function putListener() {
  var listenerToPut = this;
  EventPluginHub.putListener(listenerToPut.inst, listenerToPut.registrationName, listenerToPut.listener);
}

function inputPostMount() {
  var inst = this;
  ReactDOMInput.postMountWrapper(inst);
}

function textareaPostMount() {
  var inst = this;
  ReactDOMTextarea.postMountWrapper(inst);
}
...
```



# <a name="apidoc.module.react-dom.ReactDOMSelect"></a>[module react-dom.ReactDOMSelect](#apidoc.module.react-dom.ReactDOMSelect)

#### <a name="apidoc.element.react-dom.ReactDOMSelect.getHostProps"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMSelect.</span>getHostProps (inst, props)](#apidoc.element.react-dom.ReactDOMSelect.getHostProps)
- description and source-code
```javascript
getHostProps = function (inst, props) {
  return _assign({}, props, {
    onChange: inst._wrapperState.onChange,
    value: undefined
  });
}
```
- example usage
```shell
...
  this._wrapperState = {
    listeners: null
  };
  transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
  break;
case 'input':
  ReactDOMInput.mountWrapper(this, props, hostParent);
  props = ReactDOMInput.getHostProps(this, props);
  transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
  break;
case 'option':
  ReactDOMOption.mountWrapper(this, props, hostParent);
  props = ReactDOMOption.getHostProps(this, props);
  break;
case 'select':
...
```

#### <a name="apidoc.element.react-dom.ReactDOMSelect.getSelectValueContext"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMSelect.</span>getSelectValueContext (inst)](#apidoc.element.react-dom.ReactDOMSelect.getSelectValueContext)
- description and source-code
```javascript
getSelectValueContext = function (inst) {
  // ReactDOMOption looks at this initial value so the initial generated
  // markup has correct 'selected' attributes
  return inst._wrapperState.initialValue;
}
```
- example usage
```shell
...
  var selectParent = hostParent;

  if (selectParent._tag === 'optgroup') {
    selectParent = selectParent._hostParent;
  }

  if (selectParent != null && selectParent._tag === 'select') {
    selectValue = ReactDOMSelect.getSelectValueContext(selectParent);
  }
}

// If the value is null (e.g., no specified value or after initial mount)
// or missing (e.g., for <datalist>), we don't change props.selected
var selected = null;
if (selectValue != null) {
...
```

#### <a name="apidoc.element.react-dom.ReactDOMSelect.mountWrapper"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMSelect.</span>mountWrapper (inst, props)](#apidoc.element.react-dom.ReactDOMSelect.mountWrapper)
- description and source-code
```javascript
mountWrapper = function (inst, props) {
  if (process.env.NODE_ENV !== 'production') {
    checkSelectPropTypes(inst, props);
  }

  var value = LinkedValueUtils.getValue(props);
  inst._wrapperState = {
    pendingUpdate: false,
    initialValue: value != null ? value : props.defaultValue,
    listeners: null,
    onChange: _handleChange.bind(inst),
    wasMultiple: Boolean(props.multiple)
  };

  if (props.value !== undefined && props.defaultValue !== undefined && !didWarnValueDefaultValue) {
    process.env.NODE_ENV !== 'production' ? warning(false, 'Select elements must be either controlled or uncontrolled ' + '(specify
 either the value prop, or the defaultValue prop, but not ' + 'both). Decide between using a controlled or uncontrolled select ' + '
element and remove one of these props. More info: ' + 'https://fb.me/react-controlled-components') : void 0;
    didWarnValueDefaultValue = true;
  }
}
```
- example usage
```shell
...
case 'video':
  this._wrapperState = {
    listeners: null
  };
  transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
  break;
case 'input':
  ReactDOMInput.mountWrapper(this, props, hostParent);
  props = ReactDOMInput.getHostProps(this, props);
  transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
  break;
case 'option':
  ReactDOMOption.mountWrapper(this, props, hostParent);
  props = ReactDOMOption.getHostProps(this, props);
  break;
...
```

#### <a name="apidoc.element.react-dom.ReactDOMSelect.postUpdateWrapper"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMSelect.</span>postUpdateWrapper (inst)](#apidoc.element.react-dom.ReactDOMSelect.postUpdateWrapper)
- description and source-code
```javascript
postUpdateWrapper = function (inst) {
  var props = inst._currentElement.props;

  // After the initial mount, we control selected-ness manually so don't pass
  // this value down
  inst._wrapperState.initialValue = undefined;

  var wasMultiple = inst._wrapperState.wasMultiple;
  inst._wrapperState.wasMultiple = Boolean(props.multiple);

  var value = LinkedValueUtils.getValue(props);
  if (value != null) {
    inst._wrapperState.pendingUpdate = false;
    updateOptions(inst, Boolean(props.multiple), value);
  } else if (wasMultiple !== Boolean(props.multiple)) {
    // For simplicity, reapply 'defaultValue' if 'multiple' is toggled.
    if (props.defaultValue != null) {
      updateOptions(inst, Boolean(props.multiple), props.defaultValue);
    } else {
      // Revert the select back to its default unselected state.
      updateOptions(inst, Boolean(props.multiple), props.multiple ? [] : '');
    }
  }
}
```
- example usage
```shell
...
  case 'textarea':
    inst._wrapperState.listeners = [ReactBrowserEventEmitter.trapBubbledEvent('topInvalid', 'invalid', node)];
    break;
}
}

function postUpdateSelectWrapper() {
ReactDOMSelect.postUpdateWrapper(this);
}

// For HTML, certain tags should omit their close tag. We keep a whitelist for
// those special-case tags.

var omittedCloseTags = {
'area': true,
...
```



# <a name="apidoc.module.react-dom.ReactDOMSelection"></a>[module react-dom.ReactDOMSelection](#apidoc.module.react-dom.ReactDOMSelection)

#### <a name="apidoc.element.react-dom.ReactDOMSelection.getOffsets"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMSelection.</span>getOffsets (node)](#apidoc.element.react-dom.ReactDOMSelection.getOffsets)
- description and source-code
```javascript
function getModernOffsets(node) {
  var selection = window.getSelection && window.getSelection();

  if (!selection || selection.rangeCount === 0) {
    return null;
  }

  var anchorNode = selection.anchorNode;
  var anchorOffset = selection.anchorOffset;
  var focusNode = selection.focusNode;
  var focusOffset = selection.focusOffset;

  var currentRange = selection.getRangeAt(0);

  // In Firefox, range.startContainer and range.endContainer can be "anonymous
  // divs", e.g. the up/down buttons on an <input type="number">. Anonymous
  // divs do not seem to expose properties, triggering a "Permission denied
  // error" if any of its properties are accessed. The only seemingly possible
  // way to avoid erroring is to access a property that typically works for
  // non-anonymous divs and catch any error that may otherwise arise. See
  // https://bugzilla.mozilla.org/show_bug.cgi?id=208427
  try {
<span class="apidocCodeCommentSpan">    /* eslint-disable no-unused-expressions */
</span>    currentRange.startContainer.nodeType;
    currentRange.endContainer.nodeType;
    /* eslint-enable no-unused-expressions */
  } catch (e) {
    return null;
  }

  // If the node and offset values are the same, the selection is collapsed.
  // 'Selection.isCollapsed' is available natively, but IE sometimes gets
  // this value wrong.
  var isSelectionCollapsed = isCollapsed(selection.anchorNode, selection.anchorOffset, selection.focusNode, selection.focusOffset
);

  var rangeLength = isSelectionCollapsed ? 0 : currentRange.toString().length;

  var tempRange = currentRange.cloneRange();
  tempRange.selectNodeContents(node);
  tempRange.setEnd(currentRange.startContainer, currentRange.startOffset);

  var isTempRangeCollapsed = isCollapsed(tempRange.startContainer, tempRange.startOffset, tempRange.endContainer, tempRange.endOffset
);

  var start = isTempRangeCollapsed ? 0 : tempRange.toString().length;
  var end = start + rangeLength;

  // Detect whether the selection is backward.
  var detectionRange = document.createRange();
  detectionRange.setStart(anchorNode, anchorOffset);
  detectionRange.setEnd(focusNode, focusOffset);
  var isBackward = detectionRange.collapsed;

  return {
    start: isBackward ? end : start,
    end: isBackward ? start : end
  };
}
```
- example usage
```shell
...
      selection = {
        start: -range.moveStart('character', -input.value.length),
        end: -range.moveEnd('character', -input.value.length)
      };
    }
  } else {
    // Content editable or old IE textarea.
    selection = ReactDOMSelection.getOffsets(input);
  }

  return selection || { start: 0, end: 0 };
},

/**
 * @setSelection: Sets the selection bounds of a textarea or input and focuses
...
```

#### <a name="apidoc.element.react-dom.ReactDOMSelection.setOffsets"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMSelection.</span>setOffsets (node, offsets)](#apidoc.element.react-dom.ReactDOMSelection.setOffsets)
- description and source-code
```javascript
function setModernOffsets(node, offsets) {
  if (!window.getSelection) {
    return;
  }

  var selection = window.getSelection();
  var length = node[getTextContentAccessor()].length;
  var start = Math.min(offsets.start, length);
  var end = offsets.end === undefined ? start : Math.min(offsets.end, length);

  // IE 11 uses modern selection, but doesn't support the extend method.
  // Flip backward selections, so we can set with a single range.
  if (!selection.extend && start > end) {
    var temp = end;
    end = start;
    start = temp;
  }

  var startMarker = getNodeForCharacterOffset(node, start);
  var endMarker = getNodeForCharacterOffset(node, end);

  if (startMarker && endMarker) {
    var range = document.createRange();
    range.setStart(startMarker.node, startMarker.offset);
    selection.removeAllRanges();

    if (start > end) {
      selection.addRange(range);
      selection.extend(endMarker.node, endMarker.offset);
    } else {
      range.setEnd(endMarker.node, endMarker.offset);
      selection.addRange(range);
    }
  }
}
```
- example usage
```shell
...
    } else if (document.selection && input.nodeName && input.nodeName.toLowerCase() === 'input') {
      var range = input.createTextRange();
      range.collapse(true);
      range.moveStart('character', start);
      range.moveEnd('character', end - start);
      range.select();
    } else {
      ReactDOMSelection.setOffsets(input, offsets);
    }
  }
};

module.exports = ReactInputSelection;
...
```



# <a name="apidoc.module.react-dom.ReactDOMServer"></a>[module react-dom.ReactDOMServer](#apidoc.module.react-dom.ReactDOMServer)

#### <a name="apidoc.element.react-dom.ReactDOMServer.renderToStaticMarkup"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMServer.</span>renderToStaticMarkup (element)](#apidoc.element.react-dom.ReactDOMServer.renderToStaticMarkup)
- description and source-code
```javascript
function renderToStaticMarkup(element) {
  !React.isValidElement(element) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'renderToStaticMarkup(): You must pass
 a valid ReactElement.') : _prodInvariant('47') : void 0;
  return renderToStringImpl(element, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactDOMServer.renderToString"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMServer.</span>renderToString (element)](#apidoc.element.react-dom.ReactDOMServer.renderToString)
- description and source-code
```javascript
function renderToString(element) {
  !React.isValidElement(element) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'renderToString(): You must pass a valid
 ReactElement.') : _prodInvariant('46') : void 0;
  return renderToStringImpl(element, false);
}
```
- example usage
```shell
...

class MyComponent extends React.Component {
  render() {
    return <div>Hello World</div>;
  }
}

ReactDOMServer.renderToString(<MyComponent />);
'''

## API

### 'react-dom'

- 'findDOMNode'
...
```



# <a name="apidoc.module.react-dom.ReactDOMTextComponent"></a>[module react-dom.ReactDOMTextComponent](#apidoc.module.react-dom.ReactDOMTextComponent)

#### <a name="apidoc.element.react-dom.ReactDOMTextComponent.ReactDOMTextComponent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ReactDOMTextComponent (text)](#apidoc.element.react-dom.ReactDOMTextComponent.ReactDOMTextComponent)
- description and source-code
```javascript
ReactDOMTextComponent = function (text) {
  // TODO: This is really a ReactText (ReactNode), not a ReactElement
  this._currentElement = text;
  this._stringText = '' + text;
  // ReactDOMComponentTree uses these:
  this._hostNode = null;
  this._hostParent = null;

  // Properties
  this._domID = 0;
  this._mountIndex = 0;
  this._closingComment = null;
  this._commentNodes = null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactDOMTextComponent.prototype"></a>[module react-dom.ReactDOMTextComponent.prototype](#apidoc.module.react-dom.ReactDOMTextComponent.prototype)

#### <a name="apidoc.element.react-dom.ReactDOMTextComponent.prototype.getHostNode"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMTextComponent.prototype.</span>getHostNode ()](#apidoc.element.react-dom.ReactDOMTextComponent.prototype.getHostNode)
- description and source-code
```javascript
getHostNode = function () {
  var hostNode = this._commentNodes;
  if (hostNode) {
    return hostNode;
  }
  if (!this._closingComment) {
    var openingComment = ReactDOMComponentTree.getNodeFromInstance(this);
    var node = openingComment.nextSibling;
    while (true) {
      !(node != null) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Missing closing comment for text component %s',
this._domID) : _prodInvariant('67', this._domID) : void 0;
      if (node.nodeType === 8 && node.nodeValue === ' /react-text ') {
        this._closingComment = node;
        break;
      }
      node = node.nextSibling;
    }
  }
  hostNode = [this._hostNode, this._closingComment];
  this._commentNodes = hostNode;
  return hostNode;
}
```
- example usage
```shell
...
var prevElement = prevChild && prevChild._currentElement;
var nextElement = nextChildren[name];
if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
  ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
  nextChildren[name] = prevChild;
} else {
  if (prevChild) {
    removedNodes[name] = ReactReconciler.getHostNode(prevChild);
    ReactReconciler.unmountComponent(prevChild, false);
  }
  // The child must be instantiated before it's mounted.
  var nextChildInstance = instantiateReactComponent(nextElement, true);
  nextChildren[name] = nextChildInstance;
  // Creating mount image now ensures refs are resolved in right order
  // (see https://github.com/facebook/react/pull/7101 for explanation).
...
```

#### <a name="apidoc.element.react-dom.ReactDOMTextComponent.prototype.mountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMTextComponent.prototype.</span>mountComponent (transaction, hostParent, hostContainerInfo, context)](#apidoc.element.react-dom.ReactDOMTextComponent.prototype.mountComponent)
- description and source-code
```javascript
mountComponent = function (transaction, hostParent, hostContainerInfo, context) {
  if (process.env.NODE_ENV !== 'production') {
    var parentInfo;
    if (hostParent != null) {
      parentInfo = hostParent._ancestorInfo;
    } else if (hostContainerInfo != null) {
      parentInfo = hostContainerInfo._ancestorInfo;
    }
    if (parentInfo) {
      // parentInfo should always be present except for the top-level
      // component when server rendering
      validateDOMNesting(null, this._stringText, this, parentInfo);
    }
  }

  var domID = hostContainerInfo._idCounter++;
  var openingValue = ' react-text: ' + domID + ' ';
  var closingValue = ' /react-text ';
  this._domID = domID;
  this._hostParent = hostParent;
  if (transaction.useCreateElement) {
    var ownerDocument = hostContainerInfo._ownerDocument;
    var openingComment = ownerDocument.createComment(openingValue);
    var closingComment = ownerDocument.createComment(closingValue);
    var lazyTree = DOMLazyTree(ownerDocument.createDocumentFragment());
    DOMLazyTree.queueChild(lazyTree, DOMLazyTree(openingComment));
    if (this._stringText) {
      DOMLazyTree.queueChild(lazyTree, DOMLazyTree(ownerDocument.createTextNode(this._stringText)));
    }
    DOMLazyTree.queueChild(lazyTree, DOMLazyTree(closingComment));
    ReactDOMComponentTree.precacheNode(this, openingComment);
    this._closingComment = closingComment;
    return lazyTree;
  } else {
    var escapedText = escapeTextContentForBrowser(this._stringText);

    if (transaction.renderToStaticMarkup) {
      // Normally we'd wrap this between comment nodes for the reasons stated
      // above, but since this is a situation where React won't take over
      // (static pages), we can simply return the text as it is.
      return escapedText;
    }

    return '<!--' + openingValue + '-->' + escapedText + '<!--' + closingValue + '-->';
  }
}
```
- example usage
```shell
...
      ReactReconciler.unmountComponent(prevChild, false);
    }
    // The child must be instantiated before it's mounted.
    var nextChildInstance = instantiateReactComponent(nextElement, true);
    nextChildren[name] = nextChildInstance;
    // Creating mount image now ensures refs are resolved in right order
    // (see https://github.com/facebook/react/pull/7101 for explanation).
    var nextChildMountImage = ReactReconciler.mountComponent(nextChildInstance, transaction, hostParent, hostContainerInfo, context
, selfDebugID);
    mountImages.push(nextChildMountImage);
  }
}
// Unmount children that are no longer present.
for (name in prevChildren) {
  if (prevChildren.hasOwnProperty(name) && !(nextChildren && nextChildren.hasOwnProperty(name))) {
    prevChild = prevChildren[name];
...
```

#### <a name="apidoc.element.react-dom.ReactDOMTextComponent.prototype.receiveComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMTextComponent.prototype.</span>receiveComponent (nextText, transaction)](#apidoc.element.react-dom.ReactDOMTextComponent.prototype.receiveComponent)
- description and source-code
```javascript
receiveComponent = function (nextText, transaction) {
  if (nextText !== this._currentElement) {
    this._currentElement = nextText;
    var nextStringText = '' + nextText;
    if (nextStringText !== this._stringText) {
      // TODO: Save this as pending props and use performUpdateIfNecessary
      // and/or updateComponent to do the actual update for consistency with
      // other component types?
      this._stringText = nextStringText;
      var commentNodes = this.getHostNode();
      DOMChildrenOperations.replaceDelimitedText(commentNodes[0], commentNodes[1], nextStringText);
    }
  }
}
```
- example usage
```shell
...
if (!nextChildren.hasOwnProperty(name)) {
  continue;
}
prevChild = prevChildren && prevChildren[name];
var prevElement = prevChild && prevChild._currentElement;
var nextElement = nextChildren[name];
if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
  ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
  nextChildren[name] = prevChild;
} else {
  if (prevChild) {
    removedNodes[name] = ReactReconciler.getHostNode(prevChild);
    ReactReconciler.unmountComponent(prevChild, false);
  }
  // The child must be instantiated before it's mounted.
...
```

#### <a name="apidoc.element.react-dom.ReactDOMTextComponent.prototype.unmountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMTextComponent.prototype.</span>unmountComponent ()](#apidoc.element.react-dom.ReactDOMTextComponent.prototype.unmountComponent)
- description and source-code
```javascript
unmountComponent = function () {
  this._closingComment = null;
  this._commentNodes = null;
  ReactDOMComponentTree.uncacheNode(this);
}
```
- example usage
```shell
...
var nextElement = nextChildren[name];
if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
  ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
  nextChildren[name] = prevChild;
} else {
  if (prevChild) {
    removedNodes[name] = ReactReconciler.getHostNode(prevChild);
    ReactReconciler.unmountComponent(prevChild, false);
  }
  // The child must be instantiated before it's mounted.
  var nextChildInstance = instantiateReactComponent(nextElement, true);
  nextChildren[name] = nextChildInstance;
  // Creating mount image now ensures refs are resolved in right order
  // (see https://github.com/facebook/react/pull/7101 for explanation).
  var nextChildMountImage = ReactReconciler.mountComponent(nextChildInstance, transaction, hostParent, hostContainerInfo, context
, selfDebugID);
...
```



# <a name="apidoc.module.react-dom.ReactDOMTextarea"></a>[module react-dom.ReactDOMTextarea](#apidoc.module.react-dom.ReactDOMTextarea)

#### <a name="apidoc.element.react-dom.ReactDOMTextarea.getHostProps"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMTextarea.</span>getHostProps (inst, props)](#apidoc.element.react-dom.ReactDOMTextarea.getHostProps)
- description and source-code
```javascript
getHostProps = function (inst, props) {
  !(props.dangerouslySetInnerHTML == null) ? process.env.NODE_ENV !== 'production' ? invariant(false, ''dangerouslySetInnerHTML'
does not make sense on <textarea>.') : _prodInvariant('91') : void 0;

  // Always set children to the same thing. In IE9, the selection range will
  // get reset if 'textContent' is mutated.  We could add a check in setTextContent
  // to only set the value if/when the value differs from the node value (which would
  // completely solve this IE9 bug), but Sebastian+Ben seemed to like this solution.
  // The value can be a boolean or object so that's why it's forced to be a string.
  var hostProps = _assign({}, props, {
    value: undefined,
    defaultValue: undefined,
    children: '' + inst._wrapperState.initialValue,
    onChange: inst._wrapperState.onChange
  });

  return hostProps;
}
```
- example usage
```shell
...
  this._wrapperState = {
    listeners: null
  };
  transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
  break;
case 'input':
  ReactDOMInput.mountWrapper(this, props, hostParent);
  props = ReactDOMInput.getHostProps(this, props);
  transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
  break;
case 'option':
  ReactDOMOption.mountWrapper(this, props, hostParent);
  props = ReactDOMOption.getHostProps(this, props);
  break;
case 'select':
...
```

#### <a name="apidoc.element.react-dom.ReactDOMTextarea.mountWrapper"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMTextarea.</span>mountWrapper (inst, props)](#apidoc.element.react-dom.ReactDOMTextarea.mountWrapper)
- description and source-code
```javascript
mountWrapper = function (inst, props) {
  if (process.env.NODE_ENV !== 'production') {
    LinkedValueUtils.checkPropTypes('textarea', props, inst._currentElement._owner);
    if (props.valueLink !== undefined && !didWarnValueLink) {
      process.env.NODE_ENV !== 'production' ? warning(false, ''valueLink' prop on 'textarea' is deprecated; set 'value' and 'onChange
' instead.') : void 0;
      didWarnValueLink = true;
    }
    if (props.value !== undefined && props.defaultValue !== undefined && !didWarnValDefaultVal) {
      process.env.NODE_ENV !== 'production' ? warning(false, 'Textarea elements must be either controlled or uncontrolled ' + '(
specify either the value prop, or the defaultValue prop, but not ' + 'both). Decide between using a controlled or uncontrolled textarea
 ' + 'and remove one of these props. More info: ' + 'https://fb.me/react-controlled-components') : void 0;
      didWarnValDefaultVal = true;
    }
  }

  var value = LinkedValueUtils.getValue(props);
  var initialValue = value;

  // Only bother fetching default value if we're going to use it
  if (value == null) {
    var defaultValue = props.defaultValue;
    // TODO (yungsters): Remove support for children content in <textarea>.
    var children = props.children;
    if (children != null) {
      if (process.env.NODE_ENV !== 'production') {
        process.env.NODE_ENV !== 'production' ? warning(false, 'Use the 'defaultValue' or 'value' props instead of setting ' + '
children on <textarea>.') : void 0;
      }
      !(defaultValue == null) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'If you supply 'defaultValue' on a <textarea
>, do not pass children.') : _prodInvariant('92') : void 0;
      if (Array.isArray(children)) {
        !(children.length <= 1) ? process.env.NODE_ENV !== 'production' ? invariant(false, '<textarea> can only have at most one
 child.') : _prodInvariant('93') : void 0;
        children = children[0];
      }

      defaultValue = '' + children;
    }
    if (defaultValue == null) {
      defaultValue = '';
    }
    initialValue = defaultValue;
  }

  inst._wrapperState = {
    initialValue: '' + initialValue,
    listeners: null,
    onChange: _handleChange.bind(inst)
  };
}
```
- example usage
```shell
...
case 'video':
  this._wrapperState = {
    listeners: null
  };
  transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
  break;
case 'input':
  ReactDOMInput.mountWrapper(this, props, hostParent);
  props = ReactDOMInput.getHostProps(this, props);
  transaction.getReactMountReady().enqueue(trapBubbledEventsLocal, this);
  break;
case 'option':
  ReactDOMOption.mountWrapper(this, props, hostParent);
  props = ReactDOMOption.getHostProps(this, props);
  break;
...
```

#### <a name="apidoc.element.react-dom.ReactDOMTextarea.postMountWrapper"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMTextarea.</span>postMountWrapper (inst)](#apidoc.element.react-dom.ReactDOMTextarea.postMountWrapper)
- description and source-code
```javascript
postMountWrapper = function (inst) {
  // This is in postMount because we need access to the DOM node, which is not
  // available until after the component has mounted.
  var node = ReactDOMComponentTree.getNodeFromInstance(inst);
  var textContent = node.textContent;

  // Only set node.value if textContent is equal to the expected
  // initial value. In IE10/IE11 there is a bug where the placeholder attribute
  // will populate textContent as well.
  // https://developer.microsoft.com/microsoft-edge/platform/issues/101525/
  if (textContent === inst._wrapperState.initialValue) {
    node.value = textContent;
  }
}
```
- example usage
```shell
...
function putListener() {
  var listenerToPut = this;
  EventPluginHub.putListener(listenerToPut.inst, listenerToPut.registrationName, listenerToPut.listener);
}

function inputPostMount() {
  var inst = this;
  ReactDOMInput.postMountWrapper(inst);
}

function textareaPostMount() {
  var inst = this;
  ReactDOMTextarea.postMountWrapper(inst);
}
...
```

#### <a name="apidoc.element.react-dom.ReactDOMTextarea.updateWrapper"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMTextarea.</span>updateWrapper (inst)](#apidoc.element.react-dom.ReactDOMTextarea.updateWrapper)
- description and source-code
```javascript
updateWrapper = function (inst) {
  var props = inst._currentElement.props;

  var node = ReactDOMComponentTree.getNodeFromInstance(inst);
  var value = LinkedValueUtils.getValue(props);
  if (value != null) {
    // Cast 'value' to a string to ensure the value is set correctly. While
    // browsers typically do this as necessary, jsdom doesn't.
    var newValue = '' + value;

    // To avoid side effects (such as losing text selection), only set value if changed
    if (newValue !== node.value) {
      node.value = newValue;
    }
    if (props.defaultValue == null) {
      node.defaultValue = newValue;
    }
  }
  if (props.defaultValue != null) {
    node.defaultValue = props.defaultValue;
  }
}
```
- example usage
```shell
...
this._updateDOMChildren(lastProps, nextProps, transaction, context);

switch (this._tag) {
  case 'input':
    // Update the wrapper around inputs *after* updating props. This has to
    // happen after '_updateDOMProperties'. Otherwise HTML5 input validations
    // raise warnings and prevent the new value from being assigned.
    ReactDOMInput.updateWrapper(this);
    break;
  case 'textarea':
    ReactDOMTextarea.updateWrapper(this);
    break;
  case 'select':
    // <select> value update needs to occur after <option> children
    // reconciliation
...
```



# <a name="apidoc.module.react-dom.ReactDOMTreeTraversal"></a>[module react-dom.ReactDOMTreeTraversal](#apidoc.module.react-dom.ReactDOMTreeTraversal)

#### <a name="apidoc.element.react-dom.ReactDOMTreeTraversal.getLowestCommonAncestor"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMTreeTraversal.</span>getLowestCommonAncestor (instA, instB)](#apidoc.element.react-dom.ReactDOMTreeTraversal.getLowestCommonAncestor)
- description and source-code
```javascript
function getLowestCommonAncestor(instA, instB) {
  !('_hostNode' in instA) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'getNodeFromInstance: Invalid argument.') :
_prodInvariant('33') : void 0;
  !('_hostNode' in instB) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'getNodeFromInstance: Invalid argument.') :
_prodInvariant('33') : void 0;

  var depthA = 0;
  for (var tempA = instA; tempA; tempA = tempA._hostParent) {
    depthA++;
  }
  var depthB = 0;
  for (var tempB = instB; tempB; tempB = tempB._hostParent) {
    depthB++;
  }

  // If A is deeper, crawl up.
  while (depthA - depthB > 0) {
    instA = instA._hostParent;
    depthA--;
  }

  // If B is deeper, crawl up.
  while (depthB - depthA > 0) {
    instB = instB._hostParent;
    depthB--;
  }

  // Walk in lockstep until we find a match.
  var depth = depthA;
  while (depth--) {
    if (instA === instB) {
      return instA;
    }
    instA = instA._hostParent;
    instB = instB._hostParent;
  }
  return null;
}
```
- example usage
```shell
...
getNodeFromInstance: function (node) {
  return ComponentTree.getNodeFromInstance(node);
},
isAncestor: function (a, b) {
  return TreeTraversal.isAncestor(a, b);
},
getLowestCommonAncestor: function (a, b) {
  return TreeTraversal.getLowestCommonAncestor(a, b);
},
getParentInstance: function (inst) {
  return TreeTraversal.getParentInstance(inst);
},
traverseTwoPhase: function (target, fn, arg) {
  return TreeTraversal.traverseTwoPhase(target, fn, arg);
},
...
```

#### <a name="apidoc.element.react-dom.ReactDOMTreeTraversal.getParentInstance"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMTreeTraversal.</span>getParentInstance (inst)](#apidoc.element.react-dom.ReactDOMTreeTraversal.getParentInstance)
- description and source-code
```javascript
function getParentInstance(inst) {
  !('_hostNode' in inst) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'getParentInstance: Invalid argument.') : _prodInvariant
('36') : void 0;

  return inst._hostParent;
}
```
- example usage
```shell
...
isAncestor: function (a, b) {
  return TreeTraversal.isAncestor(a, b);
},
getLowestCommonAncestor: function (a, b) {
  return TreeTraversal.getLowestCommonAncestor(a, b);
},
getParentInstance: function (inst) {
  return TreeTraversal.getParentInstance(inst);
},
traverseTwoPhase: function (target, fn, arg) {
  return TreeTraversal.traverseTwoPhase(target, fn, arg);
},
traverseEnterLeave: function (from, to, fn, argFrom, argTo) {
  return TreeTraversal.traverseEnterLeave(from, to, fn, argFrom, argTo);
},
...
```

#### <a name="apidoc.element.react-dom.ReactDOMTreeTraversal.isAncestor"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMTreeTraversal.</span>isAncestor (instA, instB)](#apidoc.element.react-dom.ReactDOMTreeTraversal.isAncestor)
- description and source-code
```javascript
function isAncestor(instA, instB) {
  !('_hostNode' in instA) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'isAncestor: Invalid argument.') : _prodInvariant
('35') : void 0;
  !('_hostNode' in instB) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'isAncestor: Invalid argument.') : _prodInvariant
('35') : void 0;

  while (instB) {
    if (instB === instA) {
      return true;
    }
    instB = instB._hostParent;
  }
  return false;
}
```
- example usage
```shell
...
getInstanceFromNode: function (node) {
  return ComponentTree.getInstanceFromNode(node);
},
getNodeFromInstance: function (node) {
  return ComponentTree.getNodeFromInstance(node);
},
isAncestor: function (a, b) {
  return TreeTraversal.isAncestor(a, b);
},
getLowestCommonAncestor: function (a, b) {
  return TreeTraversal.getLowestCommonAncestor(a, b);
},
getParentInstance: function (inst) {
  return TreeTraversal.getParentInstance(inst);
},
...
```

#### <a name="apidoc.element.react-dom.ReactDOMTreeTraversal.traverseEnterLeave"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMTreeTraversal.</span>traverseEnterLeave (from, to, fn, argFrom, argTo)](#apidoc.element.react-dom.ReactDOMTreeTraversal.traverseEnterLeave)
- description and source-code
```javascript
function traverseEnterLeave(from, to, fn, argFrom, argTo) {
  var common = from && to ? getLowestCommonAncestor(from, to) : null;
  var pathFrom = [];
  while (from && from !== common) {
    pathFrom.push(from);
    from = from._hostParent;
  }
  var pathTo = [];
  while (to && to !== common) {
    pathTo.push(to);
    to = to._hostParent;
  }
  var i;
  for (i = 0; i < pathFrom.length; i++) {
    fn(pathFrom[i], 'bubbled', argFrom);
  }
  for (i = pathTo.length; i-- > 0;) {
    fn(pathTo[i], 'captured', argTo);
  }
}
```
- example usage
```shell
...
  getParentInstance: function (inst) {
    return TreeTraversal.getParentInstance(inst);
  },
  traverseTwoPhase: function (target, fn, arg) {
    return TreeTraversal.traverseTwoPhase(target, fn, arg);
  },
  traverseEnterLeave: function (from, to, fn, argFrom, argTo) {
    return TreeTraversal.traverseEnterLeave(from, to, fn, argFrom, argTo);
  },

  injection: injection
};

module.exports = EventPluginUtils;
...
```

#### <a name="apidoc.element.react-dom.ReactDOMTreeTraversal.traverseTwoPhase"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMTreeTraversal.</span>traverseTwoPhase (inst, fn, arg)](#apidoc.element.react-dom.ReactDOMTreeTraversal.traverseTwoPhase)
- description and source-code
```javascript
function traverseTwoPhase(inst, fn, arg) {
  var path = [];
  while (inst) {
    path.push(inst);
    inst = inst._hostParent;
  }
  var i;
  for (i = path.length; i-- > 0;) {
    fn(path[i], 'captured', arg);
  }
  for (i = 0; i < path.length; i++) {
    fn(path[i], 'bubbled', arg);
  }
}
```
- example usage
```shell
...
  getLowestCommonAncestor: function (a, b) {
    return TreeTraversal.getLowestCommonAncestor(a, b);
  },
  getParentInstance: function (inst) {
    return TreeTraversal.getParentInstance(inst);
  },
  traverseTwoPhase: function (target, fn, arg) {
    return TreeTraversal.traverseTwoPhase(target, fn, arg);
  },
  traverseEnterLeave: function (from, to, fn, argFrom, argTo) {
    return TreeTraversal.traverseEnterLeave(from, to, fn, argFrom, argTo);
  },

  injection: injection
};
...
```



# <a name="apidoc.module.react-dom.ReactDOMUnknownPropertyHook"></a>[module react-dom.ReactDOMUnknownPropertyHook](#apidoc.module.react-dom.ReactDOMUnknownPropertyHook)

#### <a name="apidoc.element.react-dom.ReactDOMUnknownPropertyHook.onBeforeMountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMUnknownPropertyHook.</span>onBeforeMountComponent (debugID, element)](#apidoc.element.react-dom.ReactDOMUnknownPropertyHook.onBeforeMountComponent)
- description and source-code
```javascript
onBeforeMountComponent = function (debugID, element) {
  handleElement(debugID, element);
}
```
- example usage
```shell
...

    validateDOMNesting(null, String(content), this, this._ancestorInfo);
    this._contentDebugID = contentDebugID;
    if (hasExistingContent) {
      ReactInstrumentation.debugTool.onBeforeUpdateComponent(contentDebugID, content);
      ReactInstrumentation.debugTool.onUpdateComponent(contentDebugID);
    } else {
      ReactInstrumentation.debugTool.onBeforeMountComponent(contentDebugID, content, debugID);
      ReactInstrumentation.debugTool.onMountComponent(contentDebugID);
      ReactInstrumentation.debugTool.onSetChildren(debugID, [contentDebugID]);
    }
  };
}

// There are so many media events, it makes sense to just
...
```

#### <a name="apidoc.element.react-dom.ReactDOMUnknownPropertyHook.onBeforeUpdateComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDOMUnknownPropertyHook.</span>onBeforeUpdateComponent (debugID, element)](#apidoc.element.react-dom.ReactDOMUnknownPropertyHook.onBeforeUpdateComponent)
- description and source-code
```javascript
onBeforeUpdateComponent = function (debugID, element) {
  handleElement(debugID, element);
}
```
- example usage
```shell
...
    this._contentDebugID = null;
    return;
  }

  validateDOMNesting(null, String(content), this, this._ancestorInfo);
  this._contentDebugID = contentDebugID;
  if (hasExistingContent) {
    ReactInstrumentation.debugTool.onBeforeUpdateComponent(contentDebugID, content);
    ReactInstrumentation.debugTool.onUpdateComponent(contentDebugID);
  } else {
    ReactInstrumentation.debugTool.onBeforeMountComponent(contentDebugID, content, debugID);
    ReactInstrumentation.debugTool.onMountComponent(contentDebugID);
    ReactInstrumentation.debugTool.onSetChildren(debugID, [contentDebugID]);
  }
};
...
```



# <a name="apidoc.module.react-dom.ReactDebugTool"></a>[module react-dom.ReactDebugTool](#apidoc.module.react-dom.ReactDebugTool)

#### <a name="apidoc.element.react-dom.ReactDebugTool.addDevtool"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>addDevtool (hook)](#apidoc.element.react-dom.ReactDebugTool.addDevtool)
- description and source-code
```javascript
addDevtool = function (hook) {
  hooks.push(hook);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.addHook"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>addHook (hook)](#apidoc.element.react-dom.ReactDebugTool.addHook)
- description and source-code
```javascript
addHook = function (hook) {
  hooks.push(hook);
}
```
- example usage
```shell
...
if (isProfiling) {
  return;
}

isProfiling = true;
flushHistory.length = 0;
resetMeasurements();
ReactDebugTool.addHook(ReactHostOperationHistoryHook);
  },
  endProfiling: function () {
if (!isProfiling) {
  return;
}

isProfiling = false;
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.beginProfiling"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>beginProfiling ()](#apidoc.element.react-dom.ReactDebugTool.beginProfiling)
- description and source-code
```javascript
beginProfiling = function () {
  if (isProfiling) {
    return;
  }

  isProfiling = true;
  flushHistory.length = 0;
  resetMeasurements();
  ReactDebugTool.addHook(ReactHostOperationHistoryHook);
}
```
- example usage
```shell
...
ReactDebugTool.addDevtool = ReactDebugTool.addHook;
ReactDebugTool.removeDevtool = ReactDebugTool.removeHook;

ReactDebugTool.addHook(ReactInvalidSetStateWarningHook);
ReactDebugTool.addHook(ReactComponentTreeHook);
var url = ExecutionEnvironment.canUseDOM && window.location.href || '';
if (/[?&]react_perf\b/.test(url)) {
  ReactDebugTool.beginProfiling();
}

module.exports = ReactDebugTool;
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.endProfiling"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>endProfiling ()](#apidoc.element.react-dom.ReactDebugTool.endProfiling)
- description and source-code
```javascript
endProfiling = function () {
  if (!isProfiling) {
    return;
  }

  isProfiling = false;
  resetMeasurements();
  ReactDebugTool.removeHook(ReactHostOperationHistoryHook);
}
```
- example usage
```shell
...

function stop() {
if (!(process.env.NODE_ENV !== 'production')) {
  warnInProduction();
  return;
}

ReactDebugTool.endProfiling();
}

function isRunning() {
if (!(process.env.NODE_ENV !== 'production')) {
  warnInProduction();
  return false;
}
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.getFlushHistory"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>getFlushHistory ()](#apidoc.element.react-dom.ReactDebugTool.getFlushHistory)
- description and source-code
```javascript
getFlushHistory = function () {
  return flushHistory;
}
```
- example usage
```shell
...

function getLastMeasurements() {
if (!(process.env.NODE_ENV !== 'production')) {
  warnInProduction();
  return [];
}

return ReactDebugTool.getFlushHistory();
}

function getExclusive() {
var flushHistory = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : getLastMeasurements();

if (!(process.env.NODE_ENV !== 'production')) {
  warnInProduction();
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.isProfiling"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>isProfiling ()](#apidoc.element.react-dom.ReactDebugTool.isProfiling)
- description and source-code
```javascript
isProfiling = function () {
  return isProfiling;
}
```
- example usage
```shell
...

function isRunning() {
if (!(process.env.NODE_ENV !== 'production')) {
  warnInProduction();
  return false;
}

return ReactDebugTool.isProfiling();
}

var ReactPerfAnalysis = {
getLastMeasurements: getLastMeasurements,
getExclusive: getExclusive,
getInclusive: getInclusive,
getWasted: getWasted,
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.onBeforeMountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onBeforeMountComponent (debugID, element, parentDebugID)](#apidoc.element.react-dom.ReactDebugTool.onBeforeMountComponent)
- description and source-code
```javascript
onBeforeMountComponent = function (debugID, element, parentDebugID) {
  checkDebugID(debugID);
  checkDebugID(parentDebugID, true);
  emitEvent('onBeforeMountComponent', debugID, element, parentDebugID);
  markBegin(debugID, 'mount');
}
```
- example usage
```shell
...

    validateDOMNesting(null, String(content), this, this._ancestorInfo);
    this._contentDebugID = contentDebugID;
    if (hasExistingContent) {
      ReactInstrumentation.debugTool.onBeforeUpdateComponent(contentDebugID, content);
      ReactInstrumentation.debugTool.onUpdateComponent(contentDebugID);
    } else {
      ReactInstrumentation.debugTool.onBeforeMountComponent(contentDebugID, content, debugID);
      ReactInstrumentation.debugTool.onMountComponent(contentDebugID);
      ReactInstrumentation.debugTool.onSetChildren(debugID, [contentDebugID]);
    }
  };
}

// There are so many media events, it makes sense to just
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.onBeforeUnmountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onBeforeUnmountComponent (debugID)](#apidoc.element.react-dom.ReactDebugTool.onBeforeUnmountComponent)
- description and source-code
```javascript
onBeforeUnmountComponent = function (debugID) {
  checkDebugID(debugID);
  emitEvent('onBeforeUnmountComponent', debugID);
  markBegin(debugID, 'unmount');
}
```
- example usage
```shell
...
 *
 * @final
 * @internal
 */
unmountComponent: function (internalInstance, safely) {
  if (process.env.NODE_ENV !== 'production') {
    if (internalInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onBeforeUnmountComponent(internalInstance._debugID);
    }
  }
  ReactRef.detachRefs(internalInstance, internalInstance._currentElement);
  internalInstance.unmountComponent(safely);
  if (process.env.NODE_ENV !== 'production') {
    if (internalInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onUnmountComponent(internalInstance._debugID);
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.onBeforeUpdateComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onBeforeUpdateComponent (debugID, element)](#apidoc.element.react-dom.ReactDebugTool.onBeforeUpdateComponent)
- description and source-code
```javascript
onBeforeUpdateComponent = function (debugID, element) {
  checkDebugID(debugID);
  emitEvent('onBeforeUpdateComponent', debugID, element);
  markBegin(debugID, 'update');
}
```
- example usage
```shell
...
    this._contentDebugID = null;
    return;
  }

  validateDOMNesting(null, String(content), this, this._ancestorInfo);
  this._contentDebugID = contentDebugID;
  if (hasExistingContent) {
    ReactInstrumentation.debugTool.onBeforeUpdateComponent(contentDebugID, content);
    ReactInstrumentation.debugTool.onUpdateComponent(contentDebugID);
  } else {
    ReactInstrumentation.debugTool.onBeforeMountComponent(contentDebugID, content, debugID);
    ReactInstrumentation.debugTool.onMountComponent(contentDebugID);
    ReactInstrumentation.debugTool.onSetChildren(debugID, [contentDebugID]);
  }
};
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.onBeginFlush"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onBeginFlush ()](#apidoc.element.react-dom.ReactDebugTool.onBeginFlush)
- description and source-code
```javascript
onBeginFlush = function () {
  currentFlushNesting++;
  resetMeasurements();
  pauseCurrentLifeCycleTimer();
  emitEvent('onBeginFlush');
}
```
- example usage
```shell
...
 * @param {DOMElement} container DOM element to unmount from.
 * @final
 * @internal
 * @see {ReactMount.unmountComponentAtNode}
 */
function unmountComponentFromNode(instance, container, safely) {
if (process.env.NODE_ENV !== 'production') {
  ReactInstrumentation.debugTool.onBeginFlush();
}
ReactReconciler.unmountComponent(instance, safely);
if (process.env.NODE_ENV !== 'production') {
  ReactInstrumentation.debugTool.onEndFlush();
}

if (container.nodeType === DOC_NODE_TYPE) {
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.onBeginLifeCycleTimer"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onBeginLifeCycleTimer (debugID, timerType)](#apidoc.element.react-dom.ReactDebugTool.onBeginLifeCycleTimer)
- description and source-code
```javascript
onBeginLifeCycleTimer = function (debugID, timerType) {
  checkDebugID(debugID);
  emitEvent('onBeginLifeCycleTimer', debugID, timerType);
  markBegin(debugID, timerType);
  beginLifeCycleTimer(debugID, timerType);
}
```
- example usage
```shell
...
  if (debugID === 0) {
    // Top-level wrappers (see ReactMount) and empty components (see
    // ReactDOMEmptyComponent) are invisible to hooks and devtools.
    // Both are implementation details that should go away in the future.
    return fn();
  }

  ReactInstrumentation.debugTool.onBeginLifeCycleTimer(debugID, timerType);
  try {
    return fn();
  } finally {
    ReactInstrumentation.debugTool.onEndLifeCycleTimer(debugID, timerType);
  }
}
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.onBeginProcessingChildContext"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onBeginProcessingChildContext ()](#apidoc.element.react-dom.ReactDebugTool.onBeginProcessingChildContext)
- description and source-code
```javascript
onBeginProcessingChildContext = function () {
  emitEvent('onBeginProcessingChildContext');
}
```
- example usage
```shell
...
  _processChildContext: function (currentContext) {
var Component = this._currentElement.type;
var inst = this._instance;
var childContext;

if (inst.getChildContext) {
  if (process.env.NODE_ENV !== 'production') {
    ReactInstrumentation.debugTool.onBeginProcessingChildContext();
    try {
      childContext = inst.getChildContext();
    } finally {
      ReactInstrumentation.debugTool.onEndProcessingChildContext();
    }
  } else {
    childContext = inst.getChildContext();
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.onEndFlush"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onEndFlush ()](#apidoc.element.react-dom.ReactDebugTool.onEndFlush)
- description and source-code
```javascript
onEndFlush = function () {
  resetMeasurements();
  currentFlushNesting--;
  resumeCurrentLifeCycleTimer();
  emitEvent('onEndFlush');
}
```
- example usage
```shell
...
 */
function unmountComponentFromNode(instance, container, safely) {
if (process.env.NODE_ENV !== 'production') {
  ReactInstrumentation.debugTool.onBeginFlush();
}
ReactReconciler.unmountComponent(instance, safely);
if (process.env.NODE_ENV !== 'production') {
  ReactInstrumentation.debugTool.onEndFlush();
}

if (container.nodeType === DOC_NODE_TYPE) {
  container = container.documentElement;
}

// http://jsperf.com/emptying-a-node
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.onEndLifeCycleTimer"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onEndLifeCycleTimer (debugID, timerType)](#apidoc.element.react-dom.ReactDebugTool.onEndLifeCycleTimer)
- description and source-code
```javascript
onEndLifeCycleTimer = function (debugID, timerType) {
  checkDebugID(debugID);
  endLifeCycleTimer(debugID, timerType);
  markEnd(debugID, timerType);
  emitEvent('onEndLifeCycleTimer', debugID, timerType);
}
```
- example usage
```shell
...
   return fn();
 }

 ReactInstrumentation.debugTool.onBeginLifeCycleTimer(debugID, timerType);
 try {
   return fn();
 } finally {
   ReactInstrumentation.debugTool.onEndLifeCycleTimer(debugID, timerType);
 }
}

/**
* ------------------ The Life-Cycle of a Composite Component ------------------
*
* - constructor: Initialization of state. The instance is now retained.
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.onEndProcessingChildContext"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onEndProcessingChildContext ()](#apidoc.element.react-dom.ReactDebugTool.onEndProcessingChildContext)
- description and source-code
```javascript
onEndProcessingChildContext = function () {
  emitEvent('onEndProcessingChildContext');
}
```
- example usage
```shell
...

if (inst.getChildContext) {
  if (process.env.NODE_ENV !== 'production') {
    ReactInstrumentation.debugTool.onBeginProcessingChildContext();
    try {
      childContext = inst.getChildContext();
    } finally {
      ReactInstrumentation.debugTool.onEndProcessingChildContext();
    }
  } else {
    childContext = inst.getChildContext();
  }
}

if (childContext) {
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.onHostOperation"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onHostOperation (operation)](#apidoc.element.react-dom.ReactDebugTool.onHostOperation)
- description and source-code
```javascript
onHostOperation = function (operation) {
  checkDebugID(operation.instanceID);
  emitEvent('onHostOperation', operation);
}
```
- example usage
```shell
...
   *
   * @param {DOMElement} node
   * @param {object} styles
   * @param {ReactDOMComponent} component
   */
  setValueForStyles: function (node, styles, component) {
if (process.env.NODE_ENV !== 'production') {
  ReactInstrumentation.debugTool.onHostOperation({
    instanceID: component._debugID,
    type: 'update styles',
    payload: styles
  });
}

var style = node.style;
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.onMountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onMountComponent (debugID)](#apidoc.element.react-dom.ReactDebugTool.onMountComponent)
- description and source-code
```javascript
onMountComponent = function (debugID) {
  checkDebugID(debugID);
  markEnd(debugID, 'mount');
  emitEvent('onMountComponent', debugID);
}
```
- example usage
```shell
...
    validateDOMNesting(null, String(content), this, this._ancestorInfo);
    this._contentDebugID = contentDebugID;
    if (hasExistingContent) {
      ReactInstrumentation.debugTool.onBeforeUpdateComponent(contentDebugID, content);
      ReactInstrumentation.debugTool.onUpdateComponent(contentDebugID);
    } else {
      ReactInstrumentation.debugTool.onBeforeMountComponent(contentDebugID, content, debugID);
      ReactInstrumentation.debugTool.onMountComponent(contentDebugID);
      ReactInstrumentation.debugTool.onSetChildren(debugID, [contentDebugID]);
    }
  };
}

// There are so many media events, it makes sense to just
// maintain a list rather than create a 'trapBubbledEvent' for each
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.onSetChildren"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onSetChildren (debugID, childDebugIDs)](#apidoc.element.react-dom.ReactDebugTool.onSetChildren)
- description and source-code
```javascript
onSetChildren = function (debugID, childDebugIDs) {
  checkDebugID(debugID);
  childDebugIDs.forEach(checkDebugID);
  emitEvent('onSetChildren', debugID, childDebugIDs);
}
```
- example usage
```shell
...
  this._renderedComponent = child;

  var markup = ReactReconciler.mountComponent(child, transaction, hostParent, hostContainerInfo, this._processChildContext(context
), debugID);

  if (process.env.NODE_ENV !== 'production') {
    if (debugID !== 0) {
      var childDebugIDs = child._debugID !== 0 ? [child._debugID] : [];
      ReactInstrumentation.debugTool.onSetChildren(debugID, childDebugIDs);
    }
  }

  return markup;
},

getHostNode: function () {
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.onSetState"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onSetState ()](#apidoc.element.react-dom.ReactDebugTool.onSetState)
- description and source-code
```javascript
onSetState = function () {
  emitEvent('onSetState');
}
```
- example usage
```shell
...
   *
   * @param {ReactClass} publicInstance The instance that should rerender.
   * @param {object} partialState Next partial state to be merged with state.
   * @internal
   */
  enqueueSetState: function (publicInstance, partialState) {
if (process.env.NODE_ENV !== 'production') {
  ReactInstrumentation.debugTool.onSetState();
  process.env.NODE_ENV !== 'production' ? warning(partialState != null, 'setState(...): You passed an undefined or null state object
; ' + 'instead, use forceUpdate().') : void 0;
}

var internalInstance = getInternalInstanceReadyForUpdate(publicInstance, 'setState');

if (!internalInstance) {
  return;
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.onTestEvent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onTestEvent ()](#apidoc.element.react-dom.ReactDebugTool.onTestEvent)
- description and source-code
```javascript
onTestEvent = function () {
  emitEvent('onTestEvent');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.onUnmountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onUnmountComponent (debugID)](#apidoc.element.react-dom.ReactDebugTool.onUnmountComponent)
- description and source-code
```javascript
onUnmountComponent = function (debugID) {
  checkDebugID(debugID);
  markEnd(debugID, 'unmount');
  emitEvent('onUnmountComponent', debugID);
}
```
- example usage
```shell
...
var hasExistingContent = this._contentDebugID != null;
var debugID = this._debugID;
// This ID represents the inlined child that has no backing instance:
var contentDebugID = -debugID;

if (content == null) {
  if (hasExistingContent) {
    ReactInstrumentation.debugTool.onUnmountComponent(this._contentDebugID);
  }
  this._contentDebugID = null;
  return;
}

validateDOMNesting(null, String(content), this, this._ancestorInfo);
this._contentDebugID = contentDebugID;
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.onUpdateComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>onUpdateComponent (debugID)](#apidoc.element.react-dom.ReactDebugTool.onUpdateComponent)
- description and source-code
```javascript
onUpdateComponent = function (debugID) {
  checkDebugID(debugID);
  markEnd(debugID, 'update');
  emitEvent('onUpdateComponent', debugID);
}
```
- example usage
```shell
...
      return;
    }

    validateDOMNesting(null, String(content), this, this._ancestorInfo);
    this._contentDebugID = contentDebugID;
    if (hasExistingContent) {
      ReactInstrumentation.debugTool.onBeforeUpdateComponent(contentDebugID, content);
      ReactInstrumentation.debugTool.onUpdateComponent(contentDebugID);
    } else {
      ReactInstrumentation.debugTool.onBeforeMountComponent(contentDebugID, content, debugID);
      ReactInstrumentation.debugTool.onMountComponent(contentDebugID);
      ReactInstrumentation.debugTool.onSetChildren(debugID, [contentDebugID]);
    }
  };
}
...
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.removeDevtool"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>removeDevtool (hook)](#apidoc.element.react-dom.ReactDebugTool.removeDevtool)
- description and source-code
```javascript
removeDevtool = function (hook) {
  for (var i = 0; i < hooks.length; i++) {
    if (hooks[i] === hook) {
      hooks.splice(i, 1);
      i--;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactDebugTool.removeHook"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDebugTool.</span>removeHook (hook)](#apidoc.element.react-dom.ReactDebugTool.removeHook)
- description and source-code
```javascript
removeHook = function (hook) {
  for (var i = 0; i < hooks.length; i++) {
    if (hooks[i] === hook) {
      hooks.splice(i, 1);
      i--;
    }
  }
}
```
- example usage
```shell
...
endProfiling: function () {
  if (!isProfiling) {
    return;
  }

  isProfiling = false;
  resetMeasurements();
  ReactDebugTool.removeHook(ReactHostOperationHistoryHook);
},
getFlushHistory: function () {
  return flushHistory;
},
onBeginFlush: function () {
  currentFlushNesting++;
  resetMeasurements();
...
```



# <a name="apidoc.module.react-dom.ReactDefaultBatchingStrategy"></a>[module react-dom.ReactDefaultBatchingStrategy](#apidoc.module.react-dom.ReactDefaultBatchingStrategy)

#### <a name="apidoc.element.react-dom.ReactDefaultBatchingStrategy.batchedUpdates"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDefaultBatchingStrategy.</span>batchedUpdates (callback, a, b, c, d, e)](#apidoc.element.react-dom.ReactDefaultBatchingStrategy.batchedUpdates)
- description and source-code
```javascript
batchedUpdates = function (callback, a, b, c, d, e) {
  var alreadyBatchingUpdates = ReactDefaultBatchingStrategy.isBatchingUpdates;

  ReactDefaultBatchingStrategy.isBatchingUpdates = true;

  // The code is written this way to avoid extra allocations
  if (alreadyBatchingUpdates) {
    return callback(a, b, c, d, e);
  } else {
    return transaction.perform(callback, null, a, b, c, d, e);
  }
}
```
- example usage
```shell
...
  //
  // Batching is necessary here in order to ensure that all event handlers run
  // before the next rerender (including event handlers attached to ancestor
  // elements instead of directly on the input). Without this, controlled
  // components don't work properly in conjunction with event bubbling because
  // the component is rerendered and the value reverted before all the event
  // handlers can run. See https://github.com/facebook/react/issues/708.
  ReactUpdates.batchedUpdates(runEventInBatch, event);
}

function runEventInBatch(event) {
  EventPluginHub.enqueueEvents(event);
  EventPluginHub.processEventQueue(false);
}
...
```



# <a name="apidoc.module.react-dom.ReactDefaultInjection"></a>[module react-dom.ReactDefaultInjection](#apidoc.module.react-dom.ReactDefaultInjection)

#### <a name="apidoc.element.react-dom.ReactDefaultInjection.inject"></a>[function <span class="apidocSignatureSpan">react-dom.ReactDefaultInjection.</span>inject ()](#apidoc.element.react-dom.ReactDefaultInjection.inject)
- description and source-code
```javascript
function inject() {
  if (alreadyInjected) {
    // TODO: This is currently true because these injections are shared between
    // the client and the server package. They should be built independently
    // and not share any injection state. Then this problem will be solved.
    return;
  }
  alreadyInjected = true;

  ReactInjection.EventEmitter.injectReactEventListener(ReactEventListener);

<span class="apidocCodeCommentSpan">  /**
   * Inject modules for resolving DOM hierarchy and plugin ordering.
   */
</span>  ReactInjection.EventPluginHub.injectEventPluginOrder(DefaultEventPluginOrder);
  ReactInjection.EventPluginUtils.injectComponentTree(ReactDOMComponentTree);
  ReactInjection.EventPluginUtils.injectTreeTraversal(ReactDOMTreeTraversal);

  /**
   * Some important event plugins included by default (without having to require
   * them).
   */
  ReactInjection.EventPluginHub.injectEventPluginsByName({
    SimpleEventPlugin: SimpleEventPlugin,
    EnterLeaveEventPlugin: EnterLeaveEventPlugin,
    ChangeEventPlugin: ChangeEventPlugin,
    SelectEventPlugin: SelectEventPlugin,
    BeforeInputEventPlugin: BeforeInputEventPlugin
  });

  ReactInjection.HostComponent.injectGenericComponentClass(ReactDOMComponent);

  ReactInjection.HostComponent.injectTextComponentClass(ReactDOMTextComponent);

  ReactInjection.DOMProperty.injectDOMPropertyConfig(ARIADOMPropertyConfig);
  ReactInjection.DOMProperty.injectDOMPropertyConfig(HTMLDOMPropertyConfig);
  ReactInjection.DOMProperty.injectDOMPropertyConfig(SVGDOMPropertyConfig);

  ReactInjection.EmptyComponent.injectEmptyComponentFactory(function (instantiate) {
    return new ReactDOMEmptyComponent(instantiate);
  });

  ReactInjection.Updates.injectReconcileTransaction(ReactReconcileTransaction);
  ReactInjection.Updates.injectBatchingStrategy(ReactDefaultBatchingStrategy);

  ReactInjection.Component.injectEnvironment(ReactComponentBrowserEnvironment);
}
```
- example usage
```shell
...

'use strict';

var ReactDefaultInjection = require('./ReactDefaultInjection');
var ReactServerRendering = require('./ReactServerRendering');
var ReactVersion = require('./ReactVersion');

ReactDefaultInjection.inject();

var ReactDOMServer = {
  renderToString: ReactServerRendering.renderToString,
  renderToStaticMarkup: ReactServerRendering.renderToStaticMarkup,
  version: ReactVersion
};
...
```



# <a name="apidoc.module.react-dom.ReactEmptyComponent"></a>[module react-dom.ReactEmptyComponent](#apidoc.module.react-dom.ReactEmptyComponent)

#### <a name="apidoc.element.react-dom.ReactEmptyComponent.create"></a>[function <span class="apidocSignatureSpan">react-dom.ReactEmptyComponent.</span>create (instantiate)](#apidoc.element.react-dom.ReactEmptyComponent.create)
- description and source-code
```javascript
create = function (instantiate) {
  return emptyComponentFactory(instantiate);
}
```
- example usage
```shell
...
SyntheticEvent.Interface = EventInterface;

if (process.env.NODE_ENV !== 'production') {
if (isProxySupported) {
  /*eslint-disable no-func-assign */
  SyntheticEvent = new Proxy(SyntheticEvent, {
    construct: function (target, args) {
      return this.apply(target, Object.create(target.prototype), args);
    },
    apply: function (constructor, that, args) {
      return new Proxy(constructor.apply(that, args), {
        set: function (target, prop, value) {
          if (prop !== 'isPersistent' && !target.constructor.Interface.hasOwnProperty(prop) && shouldBeReleasedProperties.indexOf
(prop) === -1) {
            process.env.NODE_ENV !== 'production' ? warning(didWarnForAddedNewProperty || target.isPersistent(), 'This synthetic
 event is reused for performance reasons. If you\'re ' + 'seeing this, you\'re adding a new property in the synthetic event object. ' + 'The property is never released. See ' + 'https://fb.me/react-event-pooling for more information.') : void 0;
            didWarnForAddedNewProperty = true;
...
```



# <a name="apidoc.module.react-dom.ReactErrorUtils"></a>[module react-dom.ReactErrorUtils](#apidoc.module.react-dom.ReactErrorUtils)

#### <a name="apidoc.element.react-dom.ReactErrorUtils.invokeGuardedCallback"></a>[function <span class="apidocSignatureSpan">react-dom.ReactErrorUtils.</span>invokeGuardedCallback (name, func, a)](#apidoc.element.react-dom.ReactErrorUtils.invokeGuardedCallback)
- description and source-code
```javascript
function invokeGuardedCallback(name, func, a) {
  try {
    func(a);
  } catch (x) {
    if (caughtError === null) {
      caughtError = x;
    }
  }
}
```
- example usage
```shell
...
*/
function executeDispatch(event, simulated, listener, inst) {
 var type = event.type || 'unknown-event';
 event.currentTarget = EventPluginUtils.getNodeFromInstance(inst);
 if (simulated) {
   ReactErrorUtils.invokeGuardedCallbackWithCatch(type, listener, event);
 } else {
   ReactErrorUtils.invokeGuardedCallback(type, listener, event);
 }
 event.currentTarget = null;
}

/**
* Standard/simple iteration through an event's collected dispatches.
*/
...
```

#### <a name="apidoc.element.react-dom.ReactErrorUtils.invokeGuardedCallbackWithCatch"></a>[function <span class="apidocSignatureSpan">react-dom.ReactErrorUtils.</span>invokeGuardedCallbackWithCatch (name, func, a)](#apidoc.element.react-dom.ReactErrorUtils.invokeGuardedCallbackWithCatch)
- description and source-code
```javascript
function invokeGuardedCallback(name, func, a) {
  try {
    func(a);
  } catch (x) {
    if (caughtError === null) {
      caughtError = x;
    }
  }
}
```
- example usage
```shell
...
 * @param {function} listener Application-level callback
 * @param {*} inst Internal component instance
 */
function executeDispatch(event, simulated, listener, inst) {
  var type = event.type || 'unknown-event';
  event.currentTarget = EventPluginUtils.getNodeFromInstance(inst);
  if (simulated) {
    ReactErrorUtils.invokeGuardedCallbackWithCatch(type, listener, event);
  } else {
    ReactErrorUtils.invokeGuardedCallback(type, listener, event);
  }
  event.currentTarget = null;
}

/**
...
```

#### <a name="apidoc.element.react-dom.ReactErrorUtils.rethrowCaughtError"></a>[function <span class="apidocSignatureSpan">react-dom.ReactErrorUtils.</span>rethrowCaughtError ()](#apidoc.element.react-dom.ReactErrorUtils.rethrowCaughtError)
- description and source-code
```javascript
rethrowCaughtError = function () {
  if (caughtError) {
    var error = caughtError;
    caughtError = null;
    throw error;
  }
}
```
- example usage
```shell
...
  if (simulated) {
    forEachAccumulated(processingEventQueue, executeDispatchesAndReleaseSimulated);
  } else {
    forEachAccumulated(processingEventQueue, executeDispatchesAndReleaseTopLevel);
  }
  !!eventQueue ? process.env.NODE_ENV !== 'production' ? invariant(false, 'processEventQueue(): Additional events were enqueued
while processing an event queue. Support for this has not yet been implemented.') : _prodInvariant('95') : void 0;
  // This would be a good time to rethrow if any of the event handlers threw.
  ReactErrorUtils.rethrowCaughtError();
},

/**
 * These are needed for tests only. Do not use!
 */
__purge: function () {
  listenerBank = {};
...
```



# <a name="apidoc.module.react-dom.ReactEventEmitterMixin"></a>[module react-dom.ReactEventEmitterMixin](#apidoc.module.react-dom.ReactEventEmitterMixin)

#### <a name="apidoc.element.react-dom.ReactEventEmitterMixin.handleTopLevel"></a>[function <span class="apidocSignatureSpan">react-dom.ReactEventEmitterMixin.</span>handleTopLevel (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.ReactEventEmitterMixin.handleTopLevel)
- description and source-code
```javascript
handleTopLevel = function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  var events = EventPluginHub.extractEvents(topLevelType, targetInst, nativeEvent, nativeEventTarget);
  runEventQueueInBatch(events);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactEventListener"></a>[module react-dom.ReactEventListener](#apidoc.module.react-dom.ReactEventListener)

#### <a name="apidoc.element.react-dom.ReactEventListener._handleTopLevel"></a>[function <span class="apidocSignatureSpan">react-dom.ReactEventListener.</span>_handleTopLevel (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.ReactEventListener._handleTopLevel)
- description and source-code
```javascript
_handleTopLevel = function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  var events = EventPluginHub.extractEvents(topLevelType, targetInst, nativeEvent, nativeEventTarget);
  runEventQueueInBatch(events);
}
```
- example usage
```shell
...
  do {
    bookKeeping.ancestors.push(ancestor);
    ancestor = ancestor && findParent(ancestor);
  } while (ancestor);

  for (var i = 0; i < bookKeeping.ancestors.length; i++) {
    targetInst = bookKeeping.ancestors[i];
    ReactEventListener._handleTopLevel(bookKeeping.topLevelType, targetInst, bookKeeping.nativeEvent, getEventTarget(bookKeeping
.nativeEvent));
  }
}

function scrollValueMonitor(cb) {
  var scrollPosition = getUnboundedScrollPosition(window);
  cb(scrollPosition);
}
...
```

#### <a name="apidoc.element.react-dom.ReactEventListener.dispatchEvent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactEventListener.</span>dispatchEvent (topLevelType, nativeEvent)](#apidoc.element.react-dom.ReactEventListener.dispatchEvent)
- description and source-code
```javascript
dispatchEvent = function (topLevelType, nativeEvent) {
  if (!ReactEventListener._enabled) {
    return;
  }

  var bookKeeping = TopLevelCallbackBookKeeping.getPooled(topLevelType, nativeEvent);
  try {
    // Event queue being processed in the same cycle allows
    // 'preventDefault'.
    ReactUpdates.batchedUpdates(handleTopLevelImpl, bookKeeping);
  } finally {
    TopLevelCallbackBookKeeping.release(bookKeeping);
  }
}
```
- example usage
```shell
...
    var fakeNode = document.createElement('react');
    ReactErrorUtils.invokeGuardedCallback = function (name, func, a) {
      var boundFunc = func.bind(null, a);
      var evtType = 'react-' + name;
      fakeNode.addEventListener(evtType, boundFunc, false);
      var evt = document.createEvent('Event');
      evt.initEvent(evtType, false, false);
      fakeNode.dispatchEvent(evt);
      fakeNode.removeEventListener(evtType, boundFunc, false);
    };
  }
}

module.exports = ReactErrorUtils;
...
```

#### <a name="apidoc.element.react-dom.ReactEventListener.isEnabled"></a>[function <span class="apidocSignatureSpan">react-dom.ReactEventListener.</span>isEnabled ()](#apidoc.element.react-dom.ReactEventListener.isEnabled)
- description and source-code
```javascript
isEnabled = function () {
  return ReactEventListener._enabled;
}
```
- example usage
```shell
...
  }
},

/**
 * @return {boolean} True if callbacks are enabled.
 */
isEnabled: function () {
  return !!(ReactBrowserEventEmitter.ReactEventListener && ReactBrowserEventEmitter.ReactEventListener.isEnabled());
},

/**
 * We listen for bubbled touch events on the document object.
 *
 * Firefox v8.01 (and possibly others) exhibited strange behavior when
 * mounting 'onmousemove' events at some node that was not the document
...
```

#### <a name="apidoc.element.react-dom.ReactEventListener.monitorScrollValue"></a>[function <span class="apidocSignatureSpan">react-dom.ReactEventListener.</span>monitorScrollValue (refresh)](#apidoc.element.react-dom.ReactEventListener.monitorScrollValue)
- description and source-code
```javascript
monitorScrollValue = function (refresh) {
  var callback = scrollValueMonitor.bind(null, refresh);
  EventListener.listen(window, 'scroll', callback);
}
```
- example usage
```shell
...
   */
  ensureScrollValueMonitoring: function () {
    if (hasEventPageXY === undefined) {
      hasEventPageXY = ReactBrowserEventEmitter.supportsEventPageXY();
    }
    if (!hasEventPageXY && !isMonitoringScrollValue) {
      var refresh = ViewportMetrics.refreshScrollValues;
      ReactBrowserEventEmitter.ReactEventListener.monitorScrollValue(refresh);
      isMonitoringScrollValue = true;
    }
  }

});

module.exports = ReactBrowserEventEmitter;
...
```

#### <a name="apidoc.element.react-dom.ReactEventListener.setEnabled"></a>[function <span class="apidocSignatureSpan">react-dom.ReactEventListener.</span>setEnabled (enabled)](#apidoc.element.react-dom.ReactEventListener.setEnabled)
- description and source-code
```javascript
setEnabled = function (enabled) {
  ReactEventListener._enabled = !!enabled;
}
```
- example usage
```shell
...
/**
 * Sets whether or not any created callbacks should be enabled.
 *
 * @param {boolean} enabled True if callbacks should be enabled.
 */
setEnabled: function (enabled) {
  if (ReactBrowserEventEmitter.ReactEventListener) {
    ReactBrowserEventEmitter.ReactEventListener.setEnabled(enabled);
  }
},

/**
 * @return {boolean} True if callbacks are enabled.
 */
isEnabled: function () {
...
```

#### <a name="apidoc.element.react-dom.ReactEventListener.setHandleTopLevel"></a>[function <span class="apidocSignatureSpan">react-dom.ReactEventListener.</span>setHandleTopLevel (handleTopLevel)](#apidoc.element.react-dom.ReactEventListener.setHandleTopLevel)
- description and source-code
```javascript
setHandleTopLevel = function (handleTopLevel) {
  ReactEventListener._handleTopLevel = handleTopLevel;
}
```
- example usage
```shell
...
ReactEventListener: null,

injection: {
  /**
   * @param {object} ReactEventListener
   */
  injectReactEventListener: function (ReactEventListener) {
    ReactEventListener.setHandleTopLevel(ReactBrowserEventEmitter.handleTopLevel);
    ReactBrowserEventEmitter.ReactEventListener = ReactEventListener;
  }
},

/**
 * Sets whether or not any created callbacks should be enabled.
 *
...
```

#### <a name="apidoc.element.react-dom.ReactEventListener.trapBubbledEvent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactEventListener.</span>trapBubbledEvent (topLevelType, handlerBaseName, element)](#apidoc.element.react-dom.ReactEventListener.trapBubbledEvent)
- description and source-code
```javascript
trapBubbledEvent = function (topLevelType, handlerBaseName, element) {
  if (!element) {
    return null;
  }
  return EventListener.listen(element, handlerBaseName, ReactEventListener.dispatchEvent.bind(null, topLevelType));
}
```
- example usage
```shell
...
var dependencies = EventPluginRegistry.registrationNameDependencies[registrationName];

for (var i = 0; i < dependencies.length; i++) {
  var dependency = dependencies[i];
  if (!(isListening.hasOwnProperty(dependency) && isListening[dependency])) {
    if (dependency === 'topWheel') {
      if (isEventSupported('wheel')) {
        ReactBrowserEventEmitter.ReactEventListener.trapBubbledEvent('topWheel', 'wheel', mountAt);
      } else if (isEventSupported('mousewheel')) {
        ReactBrowserEventEmitter.ReactEventListener.trapBubbledEvent('topWheel', 'mousewheel', mountAt);
      } else {
        // Firefox needs to capture a different mouse scroll event.
        // @see http://www.quirksmode.org/dom/events/tests/scroll.html
        ReactBrowserEventEmitter.ReactEventListener.trapBubbledEvent('topWheel', 'DOMMouseScroll', mountAt);
      }
...
```

#### <a name="apidoc.element.react-dom.ReactEventListener.trapCapturedEvent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactEventListener.</span>trapCapturedEvent (topLevelType, handlerBaseName, element)](#apidoc.element.react-dom.ReactEventListener.trapCapturedEvent)
- description and source-code
```javascript
trapCapturedEvent = function (topLevelType, handlerBaseName, element) {
  if (!element) {
    return null;
  }
  return EventListener.capture(element, handlerBaseName, ReactEventListener.dispatchEvent.bind(null, topLevelType));
}
```
- example usage
```shell
...
  // Firefox needs to capture a different mouse scroll event.
  // @see http://www.quirksmode.org/dom/events/tests/scroll.html
  ReactBrowserEventEmitter.ReactEventListener.trapBubbledEvent('topWheel', 'DOMMouseScroll', mountAt);
}
        } else if (dependency === 'topScroll') {

if (isEventSupported('scroll', true)) {
  ReactBrowserEventEmitter.ReactEventListener.trapCapturedEvent('topScroll', 'scroll', mountAt);
} else {
  ReactBrowserEventEmitter.ReactEventListener.trapBubbledEvent('topScroll', 'scroll', ReactBrowserEventEmitter.ReactEventListener
.WINDOW_HANDLE);
}
        } else if (dependency === 'topFocus' || dependency === 'topBlur') {

if (isEventSupported('focus', true)) {
  ReactBrowserEventEmitter.ReactEventListener.trapCapturedEvent('topFocus', 'focus', mountAt);
...
```



# <a name="apidoc.module.react-dom.ReactFiber"></a>[module react-dom.ReactFiber](#apidoc.module.react-dom.ReactFiber)

#### <a name="apidoc.element.react-dom.ReactFiber.cloneFiber"></a>[function <span class="apidocSignatureSpan">react-dom.ReactFiber.</span>cloneFiber (fiber, priorityLevel)](#apidoc.element.react-dom.ReactFiber.cloneFiber)
- description and source-code
```javascript
cloneFiber = function (fiber, priorityLevel) {
  // We clone to get a work in progress. That means that this fiber is the
  // current. To make it safe to reuse that fiber later on as work in progress
  // we need to reset its work in progress flag now. We don't have an
  // opportunity to do this earlier since we don't traverse the tree when
  // the work in progress tree becomes the current tree.
  // fiber.progressedPriority = NoWork;
  // fiber.progressedChild = null;

  // We use a double buffering pooling technique because we know that we'll only
  // ever need at most two versions of a tree. We pool the "other" unused node
  // that we're free to reuse. This is lazily created to avoid allocating extra
  // objects for things that are never updated. It also allow us to reclaim the
  // extra memory if needed.
  var alt = fiber.alternate;
  if (alt) {
    // Whenever we clone, we do so to get a new work in progress.
    // This ensures that we've reset these in the new tree.
    alt.nextEffect = null;
    alt.firstEffect = null;
    alt.lastEffect = null;
  } else {
    // This should not have an alternate already
    alt = createFiber(fiber.tag, fiber.key);
    alt.type = fiber.type;

    alt.progressedChild = fiber.progressedChild;
    alt.progressedPriority = fiber.progressedPriority;

    alt.alternate = fiber;
    fiber.alternate = alt;
  }

  alt.stateNode = fiber.stateNode;
  alt.child = fiber.child;
  alt.sibling = fiber.sibling; // This should always be overridden. TODO: null
  alt.ref = fiber.ref;
  // pendingProps is here for symmetry but is unnecessary in practice for now.
  // TODO: Pass in the new pendingProps as an argument maybe?
  alt.pendingProps = fiber.pendingProps;
  alt.updateQueue = fiber.updateQueue;
  alt.callbackList = fiber.callbackList;
  alt.pendingWorkPriority = priorityLevel;

  alt.memoizedProps = fiber.memoizedProps;
  alt.output = fiber.output;

  return alt;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactFiber.createFiberFromCoroutine"></a>[function <span class="apidocSignatureSpan">react-dom.ReactFiber.</span>createFiberFromCoroutine (coroutine, priorityLevel)](#apidoc.element.react-dom.ReactFiber.createFiberFromCoroutine)
- description and source-code
```javascript
createFiberFromCoroutine = function (coroutine, priorityLevel) {
  var fiber = createFiber(CoroutineComponent, coroutine.key);
  fiber.type = coroutine.handler;
  fiber.pendingProps = coroutine;
  fiber.pendingWorkPriority = priorityLevel;
  return fiber;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactFiber.createFiberFromElement"></a>[function <span class="apidocSignatureSpan">react-dom.ReactFiber.</span>createFiberFromElement (element, priorityLevel)](#apidoc.element.react-dom.ReactFiber.createFiberFromElement)
- description and source-code
```javascript
createFiberFromElement = function (element, priorityLevel) {
  // $FlowFixMe: ReactElement.key is currently defined as ?string but should be defined as null | string in Flow.
  var fiber = createFiberFromElementType(element.type, element.key);
  fiber.pendingProps = element.props;
  fiber.pendingWorkPriority = priorityLevel;
  return fiber;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactFiber.createFiberFromElementType"></a>[function <span class="apidocSignatureSpan">react-dom.ReactFiber.</span>createFiberFromElementType (type, key)](#apidoc.element.react-dom.ReactFiber.createFiberFromElementType)
- description and source-code
```javascript
function createFiberFromElementType(type, key) {
  var fiber = void 0;
  if (typeof type === 'function') {
    fiber = shouldConstruct(type) ? createFiber(ClassComponent, key) : createFiber(IndeterminateComponent, key);
    fiber.type = type;
  } else if (typeof type === 'string') {
    fiber = createFiber(HostComponent, key);
    fiber.type = type;
  } else if (typeof type === 'object' && type !== null) {
    // Currently assumed to be a continuation and therefore is a fiber already.
    fiber = type;
  } else {
    throw new Error('Unknown component type: ' + typeof type);
  }
  return fiber;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactFiber.createFiberFromYield"></a>[function <span class="apidocSignatureSpan">react-dom.ReactFiber.</span>createFiberFromYield (yieldNode, priorityLevel)](#apidoc.element.react-dom.ReactFiber.createFiberFromYield)
- description and source-code
```javascript
createFiberFromYield = function (yieldNode, priorityLevel) {
  var fiber = createFiber(YieldComponent, yieldNode.key);
  fiber.pendingProps = {};
  return fiber;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactFiber.createHostContainerFiber"></a>[function <span class="apidocSignatureSpan">react-dom.ReactFiber.</span>createHostContainerFiber ()](#apidoc.element.react-dom.ReactFiber.createHostContainerFiber)
- description and source-code
```javascript
createHostContainerFiber = function () {
  var fiber = createFiber(HostContainer, null);
  return fiber;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactFiberRoot"></a>[module react-dom.ReactFiberRoot](#apidoc.module.react-dom.ReactFiberRoot)

#### <a name="apidoc.element.react-dom.ReactFiberRoot.createFiberRoot"></a>[function <span class="apidocSignatureSpan">react-dom.ReactFiberRoot.</span>createFiberRoot (containerInfo)](#apidoc.element.react-dom.ReactFiberRoot.createFiberRoot)
- description and source-code
```javascript
createFiberRoot = function (containerInfo) {
  // Cyclic construction. This cheats the type system right now because
  // stateNode is any.
  var uninitializedFiber = createHostContainerFiber();
  var root = {
    current: uninitializedFiber,
    containerInfo: containerInfo,
    isScheduled: false,
    nextScheduledRoot: null
  };
  uninitializedFiber.stateNode = root;
  return root;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactFiberUpdateQueue"></a>[module react-dom.ReactFiberUpdateQueue](#apidoc.module.react-dom.ReactFiberUpdateQueue)

#### <a name="apidoc.element.react-dom.ReactFiberUpdateQueue.addCallbackToQueue"></a>[function <span class="apidocSignatureSpan">react-dom.ReactFiberUpdateQueue.</span>addCallbackToQueue (queue, callback)](#apidoc.element.react-dom.ReactFiberUpdateQueue.addCallbackToQueue)
- description and source-code
```javascript
addCallbackToQueue = function (queue, callback) {
  if (queue.tail.callback) {
    // If the tail already as a callback, add an empty node to queue
    exports.addToQueue(queue, null);
  }
  queue.tail.callback = callback;
  return queue;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactFiberUpdateQueue.addToQueue"></a>[function <span class="apidocSignatureSpan">react-dom.ReactFiberUpdateQueue.</span>addToQueue (queue, partialState)](#apidoc.element.react-dom.ReactFiberUpdateQueue.addToQueue)
- description and source-code
```javascript
addToQueue = function (queue, partialState) {
  var node = {
    partialState: partialState,
    callback: null,
    callbackWasCalled: false,
    next: null
  };
  queue.tail.next = node;
  queue.tail = node;
  return queue;
}
```
- example usage
```shell
...
queue.tail = node;
return queue;
};

exports.addCallbackToQueue = function (queue, callback) {
if (queue.tail.callback) {
  // If the tail already as a callback, add an empty node to queue
  exports.addToQueue(queue, null);
}
queue.tail.callback = callback;
return queue;
};

exports.callCallbacks = function (queue, context) {
var node = queue;
...
```

#### <a name="apidoc.element.react-dom.ReactFiberUpdateQueue.callCallbacks"></a>[function <span class="apidocSignatureSpan">react-dom.ReactFiberUpdateQueue.</span>callCallbacks (queue, context)](#apidoc.element.react-dom.ReactFiberUpdateQueue.callCallbacks)
- description and source-code
```javascript
callCallbacks = function (queue, context) {
  var node = queue;
  while (node) {
    if (node.callback && !node.callbackWasCalled) {
      node.callbackWasCalled = true;
      node.callback.call(context);
    }
    node = node.next;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactFiberUpdateQueue.createUpdateQueue"></a>[function <span class="apidocSignatureSpan">react-dom.ReactFiberUpdateQueue.</span>createUpdateQueue (partialState)](#apidoc.element.react-dom.ReactFiberUpdateQueue.createUpdateQueue)
- description and source-code
```javascript
createUpdateQueue = function (partialState) {
  var queue = {
    partialState: partialState,
    callback: null,
    callbackWasCalled: false,
    next: null,
    isReplace: false,
    isForced: false,
    tail: null
  };
  queue.tail = queue;
  return queue;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactFiberUpdateQueue.mergeUpdateQueue"></a>[function <span class="apidocSignatureSpan">react-dom.ReactFiberUpdateQueue.</span>mergeUpdateQueue (queue, prevState, props)](#apidoc.element.react-dom.ReactFiberUpdateQueue.mergeUpdateQueue)
- description and source-code
```javascript
mergeUpdateQueue = function (queue, prevState, props) {
  var node = queue;
  var state = queue.isReplace ? null : _assign({}, prevState);
  while (node) {
    var _partialState = void 0;
    if (typeof node.partialState === 'function') {
      var updateFn = node.partialState;
      _partialState = updateFn(state, props);
    } else {
      _partialState = node.partialState;
    }
    state = _assign(state || {}, _partialState);
    node = node.next;
  }
  return state;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactHostComponent"></a>[module react-dom.ReactHostComponent](#apidoc.module.react-dom.ReactHostComponent)

#### <a name="apidoc.element.react-dom.ReactHostComponent.createInstanceForText"></a>[function <span class="apidocSignatureSpan">react-dom.ReactHostComponent.</span>createInstanceForText (text)](#apidoc.element.react-dom.ReactHostComponent.createInstanceForText)
- description and source-code
```javascript
function createInstanceForText(text) {
  return new textComponentClass(text);
}
```
- example usage
```shell
...
    if (!instance.getHostNode) {
      instance.getHostNode = instance.getNativeNode;
    }
  } else {
    instance = new ReactCompositeComponentWrapper(element);
  }
} else if (typeof node === 'string' || typeof node === 'number') {
  instance = ReactHostComponent.createInstanceForText(node);
} else {
  !false ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Encountered invalid React node of type %s', typeof node) :
_prodInvariant('131', typeof node) : void 0;
}

if (process.env.NODE_ENV !== 'production') {
  process.env.NODE_ENV !== 'production' ? warning(typeof instance.mountComponent === 'function' && typeof instance.receiveComponent
 === 'function' && typeof instance.getHostNode === 'function' && typeof instance.unmountComponent === 'function', 'Only React Components
 can be mounted.') : void 0;
}
...
```

#### <a name="apidoc.element.react-dom.ReactHostComponent.createInternalComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactHostComponent.</span>createInternalComponent (element)](#apidoc.element.react-dom.ReactHostComponent.createInternalComponent)
- description and source-code
```javascript
function createInternalComponent(element) {
  !genericComponentClass ? process.env.NODE_ENV !== 'production' ? invariant(false, 'There is no registered component for the tag
 %s', element.type) : _prodInvariant('111', element.type) : void 0;
  return new genericComponentClass(element);
}
```
- example usage
```shell
...
}
info += getDeclarationErrorAddendum(element._owner);
!false ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Element type is invalid: expected a string (for built-in components
) or a class/function (for composite components) but got: %s.%s', type == null ? type : typeof type, info) : _prodInvariant('130
', type == null ? type : typeof type, info) : void 0;
    }

    // Special case string values
    if (typeof element.type === 'string') {
instance = ReactHostComponent.createInternalComponent(element);
    } else if (isInternalComponentType(element.type)) {
// This is temporarily available for custom components that are not string
// representations. I.e. ART. Once those are updated to use the string
// representation, we can drop this code path.
instance = new element.type(element);

// We renamed this. Allow the old name for compat. :(
...
```

#### <a name="apidoc.element.react-dom.ReactHostComponent.isTextComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactHostComponent.</span>isTextComponent (component)](#apidoc.element.react-dom.ReactHostComponent.isTextComponent)
- description and source-code
```javascript
function isTextComponent(component) {
  return component instanceof textComponentClass;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactHostOperationHistoryHook"></a>[module react-dom.ReactHostOperationHistoryHook](#apidoc.module.react-dom.ReactHostOperationHistoryHook)

#### <a name="apidoc.element.react-dom.ReactHostOperationHistoryHook.clearHistory"></a>[function <span class="apidocSignatureSpan">react-dom.ReactHostOperationHistoryHook.</span>clearHistory ()](#apidoc.element.react-dom.ReactHostOperationHistoryHook.clearHistory)
- description and source-code
```javascript
clearHistory = function () {
  if (ReactHostOperationHistoryHook._preventClearing) {
    // Should only be used for tests.
    return;
  }

  history = [];
}
```
- example usage
```shell
...
var currentTimerNestedFlushDuration = 0;
var currentTimerType = null;

var lifeCycleTimerHasWarned = false;

function clearHistory() {
ReactComponentTreeHook.purgeUnmountedComponents();
ReactHostOperationHistoryHook.clearHistory();
}

function getTreeSnapshot(registeredIDs) {
return registeredIDs.reduce(function (tree, id) {
  var ownerID = ReactComponentTreeHook.getOwnerID(id);
  var parentID = ReactComponentTreeHook.getParentID(id);
  tree[id] = {
...
```

#### <a name="apidoc.element.react-dom.ReactHostOperationHistoryHook.getHistory"></a>[function <span class="apidocSignatureSpan">react-dom.ReactHostOperationHistoryHook.</span>getHistory ()](#apidoc.element.react-dom.ReactHostOperationHistoryHook.getHistory)
- description and source-code
```javascript
getHistory = function () {
  return history;
}
```
- example usage
```shell
...
  return tree;
}, {});
}

function resetMeasurements() {
var previousStartTime = currentFlushStartTime;
var previousMeasurements = currentFlushMeasurements;
var previousOperations = ReactHostOperationHistoryHook.getHistory();

if (currentFlushNesting === 0) {
  currentFlushStartTime = 0;
  currentFlushMeasurements = [];
  clearHistory();
  return;
}
...
```

#### <a name="apidoc.element.react-dom.ReactHostOperationHistoryHook.onHostOperation"></a>[function <span class="apidocSignatureSpan">react-dom.ReactHostOperationHistoryHook.</span>onHostOperation (operation)](#apidoc.element.react-dom.ReactHostOperationHistoryHook.onHostOperation)
- description and source-code
```javascript
onHostOperation = function (operation) {
  history.push(operation);
}
```
- example usage
```shell
...
   *
   * @param {DOMElement} node
   * @param {object} styles
   * @param {ReactDOMComponent} component
   */
  setValueForStyles: function (node, styles, component) {
if (process.env.NODE_ENV !== 'production') {
  ReactInstrumentation.debugTool.onHostOperation({
    instanceID: component._debugID,
    type: 'update styles',
    payload: styles
  });
}

var style = node.style;
...
```



# <a name="apidoc.module.react-dom.ReactInputSelection"></a>[module react-dom.ReactInputSelection](#apidoc.module.react-dom.ReactInputSelection)

#### <a name="apidoc.element.react-dom.ReactInputSelection.getSelection"></a>[function <span class="apidocSignatureSpan">react-dom.ReactInputSelection.</span>getSelection (input)](#apidoc.element.react-dom.ReactInputSelection.getSelection)
- description and source-code
```javascript
getSelection = function (input) {
  var selection;

  if ('selectionStart' in input) {
    // Modern browser with input or textarea.
    selection = {
      start: input.selectionStart,
      end: input.selectionEnd
    };
  } else if (document.selection && input.nodeName && input.nodeName.toLowerCase() === 'input') {
    // IE8 input.
    var range = document.selection.createRange();
    // There can only be one selection per document in IE, so it must
    // be in our element.
    if (range.parentElement() === input) {
      selection = {
        start: -range.moveStart('character', -input.value.length),
        end: -range.moveEnd('character', -input.value.length)
      };
    }
  } else {
    // Content editable or old IE textarea.
    selection = ReactDOMSelection.getOffsets(input);
  }

  return selection || { start: 0, end: 0 };
}
```
- example usage
```shell
...
}

/**
 * @param {DOMElement} node
 * @return {?object}
 */
function getModernOffsets(node) {
var selection = window.getSelection && window.getSelection();

if (!selection || selection.rangeCount === 0) {
  return null;
}

var anchorNode = selection.anchorNode;
var anchorOffset = selection.anchorOffset;
...
```

#### <a name="apidoc.element.react-dom.ReactInputSelection.getSelectionInformation"></a>[function <span class="apidocSignatureSpan">react-dom.ReactInputSelection.</span>getSelectionInformation ()](#apidoc.element.react-dom.ReactInputSelection.getSelectionInformation)
- description and source-code
```javascript
getSelectionInformation = function () {
  var focusedElem = getActiveElement();
  return {
    focusedElem: focusedElem,
    selectionRange: ReactInputSelection.hasSelectionCapabilities(focusedElem) ? ReactInputSelection.getSelection(focusedElem) :
null
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactInputSelection.hasSelectionCapabilities"></a>[function <span class="apidocSignatureSpan">react-dom.ReactInputSelection.</span>hasSelectionCapabilities (elem)](#apidoc.element.react-dom.ReactInputSelection.hasSelectionCapabilities)
- description and source-code
```javascript
hasSelectionCapabilities = function (elem) {
  var nodeName = elem && elem.nodeName && elem.nodeName.toLowerCase();
  return nodeName && (nodeName === 'input' && elem.type === 'text' || nodeName === 'textarea' || elem.contentEditable === 'true');
}
```
- example usage
```shell
...
  return nodeName && (nodeName === 'input' && elem.type === 'text' || nodeName === 'textarea' || elem.contentEditable === 'true');
},

getSelectionInformation: function () {
  var focusedElem = getActiveElement();
  return {
    focusedElem: focusedElem,
    selectionRange: ReactInputSelection.hasSelectionCapabilities(focusedElem) ? ReactInputSelection.getSelection(focusedElem) :
null
  };
},

/**
 * @restoreSelection: If any selection information was potentially lost,
 * restore it. This is useful when performing operations that could remove dom
 * nodes and place them back in, resulting in focus being lost.
...
```

#### <a name="apidoc.element.react-dom.ReactInputSelection.restoreSelection"></a>[function <span class="apidocSignatureSpan">react-dom.ReactInputSelection.</span>restoreSelection (priorSelectionInformation)](#apidoc.element.react-dom.ReactInputSelection.restoreSelection)
- description and source-code
```javascript
restoreSelection = function (priorSelectionInformation) {
  var curFocusedElem = getActiveElement();
  var priorFocusedElem = priorSelectionInformation.focusedElem;
  var priorSelectionRange = priorSelectionInformation.selectionRange;
  if (curFocusedElem !== priorFocusedElem && isInDocument(priorFocusedElem)) {
    if (ReactInputSelection.hasSelectionCapabilities(priorFocusedElem)) {
      ReactInputSelection.setSelection(priorFocusedElem, priorSelectionRange);
    }
    focusNode(priorFocusedElem);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactInputSelection.setSelection"></a>[function <span class="apidocSignatureSpan">react-dom.ReactInputSelection.</span>setSelection (input, offsets)](#apidoc.element.react-dom.ReactInputSelection.setSelection)
- description and source-code
```javascript
setSelection = function (input, offsets) {
  var start = offsets.start;
  var end = offsets.end;
  if (end === undefined) {
    end = start;
  }

  if ('selectionStart' in input) {
    input.selectionStart = start;
    input.selectionEnd = Math.min(end, input.value.length);
  } else if (document.selection && input.nodeName && input.nodeName.toLowerCase() === 'input') {
    var range = input.createTextRange();
    range.collapse(true);
    range.moveStart('character', start);
    range.moveEnd('character', end - start);
    range.select();
  } else {
    ReactDOMSelection.setOffsets(input, offsets);
  }
}
```
- example usage
```shell
...
 */
restoreSelection: function (priorSelectionInformation) {
  var curFocusedElem = getActiveElement();
  var priorFocusedElem = priorSelectionInformation.focusedElem;
  var priorSelectionRange = priorSelectionInformation.selectionRange;
  if (curFocusedElem !== priorFocusedElem && isInDocument(priorFocusedElem)) {
    if (ReactInputSelection.hasSelectionCapabilities(priorFocusedElem)) {
      ReactInputSelection.setSelection(priorFocusedElem, priorSelectionRange);
    }
    focusNode(priorFocusedElem);
  }
},

/**
 * @getSelection: Gets the selection bounds of a focused textarea, input or
...
```



# <a name="apidoc.module.react-dom.ReactInstanceMap"></a>[module react-dom.ReactInstanceMap](#apidoc.module.react-dom.ReactInstanceMap)

#### <a name="apidoc.element.react-dom.ReactInstanceMap.get"></a>[function <span class="apidocSignatureSpan">react-dom.ReactInstanceMap.</span>get (key)](#apidoc.element.react-dom.ReactInstanceMap.get)
- description and source-code
```javascript
get = function (key) {
  return key._reactInternalInstance;
}
```
- example usage
```shell
...
ImpureClass: 0,
PureClass: 1,
StatelessFunctional: 2
};

function StatelessComponent(Component) {}
StatelessComponent.prototype.render = function () {
var Component = ReactInstanceMap.get(this)._currentElement.type;
var element = Component(this.props, this.context, this.updater);
warnIfInvalidElement(Component, element);
return element;
};

function warnIfInvalidElement(Component, element) {
if (process.env.NODE_ENV !== 'production') {
...
```

#### <a name="apidoc.element.react-dom.ReactInstanceMap.has"></a>[function <span class="apidocSignatureSpan">react-dom.ReactInstanceMap.</span>has (key)](#apidoc.element.react-dom.ReactInstanceMap.has)
- description and source-code
```javascript
has = function (key) {
  return key._reactInternalInstance !== undefined;
}
```
- example usage
```shell
...
 * @param {ReactComponent} parentComponent The conceptual parent of this render tree.
 * @param {ReactElement} nextElement Component element to render.
 * @param {DOMElement} container DOM element to render into.
 * @param {?function} callback function triggered on completion
 * @return {ReactComponent} Component instance rendered in 'container'.
 */
renderSubtreeIntoContainer: function (parentComponent, nextElement, container, callback) {
  !(parentComponent != null && ReactInstanceMap.has(parentComponent)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '
parentComponent must be a valid React Component') : _prodInvariant('38') : void 0;
  return ReactMount._renderSubtreeIntoContainer(parentComponent, nextElement, container, callback);
},

_renderSubtreeIntoContainer: function (parentComponent, nextElement, container, callback) {
  ReactUpdateQueue.validateCallback(callback, 'ReactDOM.render');
  !React.isValidElement(nextElement) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'ReactDOM.render(): Invalid component
 element.%s', typeof nextElement === 'string' ? ' Instead of passing a string like\'div\', pass ' + 'React.createElement(\'div\') or <div />.' : typeof nextElement === 'function' ? ' Instead of passing a class like Foo, pass ' + 'React.createElement(Foo) or <Foo />.' :
  // Check if it quacks like an element
...
```

#### <a name="apidoc.element.react-dom.ReactInstanceMap.remove"></a>[function <span class="apidocSignatureSpan">react-dom.ReactInstanceMap.</span>remove (key)](#apidoc.element.react-dom.ReactInstanceMap.remove)
- description and source-code
```javascript
remove = function (key) {
  key._reactInternalInstance = undefined;
}
```
- example usage
```shell
...
  this._context = null;
  this._rootNodeID = 0;
  this._topLevelWrapper = null;

  // Delete the reference from the instance to this internal representation
  // which allow the internals to be properly cleaned up even if the user
  // leaks a reference to the public instance.
  ReactInstanceMap.remove(inst);

  // Some existing components rely on inst.props even after they've been
  // destroyed (in event handlers).
  // TODO: inst.props = null;
  // TODO: inst.state = null;
  // TODO: inst.context = null;
},
...
```

#### <a name="apidoc.element.react-dom.ReactInstanceMap.set"></a>[function <span class="apidocSignatureSpan">react-dom.ReactInstanceMap.</span>set (key, value)](#apidoc.element.react-dom.ReactInstanceMap.set)
- description and source-code
```javascript
set = function (key, value) {
  key._reactInternalInstance = value;
}
```
- example usage
```shell
...
inst.context = publicContext;
inst.refs = emptyObject;
inst.updater = updateQueue;

this._instance = inst;

// Store a reference from the instance back to the internal representation
ReactInstanceMap.set(inst, this);

if (process.env.NODE_ENV !== 'production') {
  // Since plain JS classes are defined without any special initialization
  // logic, we can not catch common errors early. Therefore, we have to
  // catch them here, at initialization time, instead.
  process.env.NODE_ENV !== 'production' ? warning(!inst.getInitialState || inst.getInitialState.isReactClassApproved || inst.state
, 'getInitialState was defined on %s, a plain JavaScript class. ' + 'This is only supported for classes created using React.createClass
. ' + 'Did you mean to define a state property instead?', this.getName() || 'a component') : void 0;
  process.env.NODE_ENV !== 'production' ? warning(!inst.getDefaultProps || inst.getDefaultProps.isReactClassApproved, 'getDefaultProps
 was defined on %s, a plain JavaScript class. ' + 'This is only supported for classes created using React.createClass. ' + 'Use
a static property to define defaultProps instead.', this.getName() || 'a component') : void 0;
...
```



# <a name="apidoc.module.react-dom.ReactInvalidSetStateWarningHook"></a>[module react-dom.ReactInvalidSetStateWarningHook](#apidoc.module.react-dom.ReactInvalidSetStateWarningHook)

#### <a name="apidoc.element.react-dom.ReactInvalidSetStateWarningHook.onBeginProcessingChildContext"></a>[function <span class="apidocSignatureSpan">react-dom.ReactInvalidSetStateWarningHook.</span>onBeginProcessingChildContext ()](#apidoc.element.react-dom.ReactInvalidSetStateWarningHook.onBeginProcessingChildContext)
- description and source-code
```javascript
onBeginProcessingChildContext = function () {
  processingChildContext = true;
}
```
- example usage
```shell
...
  _processChildContext: function (currentContext) {
var Component = this._currentElement.type;
var inst = this._instance;
var childContext;

if (inst.getChildContext) {
  if (process.env.NODE_ENV !== 'production') {
    ReactInstrumentation.debugTool.onBeginProcessingChildContext();
    try {
      childContext = inst.getChildContext();
    } finally {
      ReactInstrumentation.debugTool.onEndProcessingChildContext();
    }
  } else {
    childContext = inst.getChildContext();
...
```

#### <a name="apidoc.element.react-dom.ReactInvalidSetStateWarningHook.onEndProcessingChildContext"></a>[function <span class="apidocSignatureSpan">react-dom.ReactInvalidSetStateWarningHook.</span>onEndProcessingChildContext ()](#apidoc.element.react-dom.ReactInvalidSetStateWarningHook.onEndProcessingChildContext)
- description and source-code
```javascript
onEndProcessingChildContext = function () {
  processingChildContext = false;
}
```
- example usage
```shell
...

if (inst.getChildContext) {
  if (process.env.NODE_ENV !== 'production') {
    ReactInstrumentation.debugTool.onBeginProcessingChildContext();
    try {
      childContext = inst.getChildContext();
    } finally {
      ReactInstrumentation.debugTool.onEndProcessingChildContext();
    }
  } else {
    childContext = inst.getChildContext();
  }
}

if (childContext) {
...
```

#### <a name="apidoc.element.react-dom.ReactInvalidSetStateWarningHook.onSetState"></a>[function <span class="apidocSignatureSpan">react-dom.ReactInvalidSetStateWarningHook.</span>onSetState ()](#apidoc.element.react-dom.ReactInvalidSetStateWarningHook.onSetState)
- description and source-code
```javascript
onSetState = function () {
  warnInvalidSetState();
}
```
- example usage
```shell
...
   *
   * @param {ReactClass} publicInstance The instance that should rerender.
   * @param {object} partialState Next partial state to be merged with state.
   * @internal
   */
  enqueueSetState: function (publicInstance, partialState) {
if (process.env.NODE_ENV !== 'production') {
  ReactInstrumentation.debugTool.onSetState();
  process.env.NODE_ENV !== 'production' ? warning(partialState != null, 'setState(...): You passed an undefined or null state object
; ' + 'instead, use forceUpdate().') : void 0;
}

var internalInstance = getInternalInstanceReadyForUpdate(publicInstance, 'setState');

if (!internalInstance) {
  return;
...
```



# <a name="apidoc.module.react-dom.ReactMarkupChecksum"></a>[module react-dom.ReactMarkupChecksum](#apidoc.module.react-dom.ReactMarkupChecksum)

#### <a name="apidoc.element.react-dom.ReactMarkupChecksum.addChecksumToMarkup"></a>[function <span class="apidocSignatureSpan">react-dom.ReactMarkupChecksum.</span>addChecksumToMarkup (markup)](#apidoc.element.react-dom.ReactMarkupChecksum.addChecksumToMarkup)
- description and source-code
```javascript
addChecksumToMarkup = function (markup) {
  var checksum = adler32(markup);

  // Add checksum (handle both parent tags, comments and self-closing tags)
  if (COMMENT_START.test(markup)) {
    return markup;
  } else {
    return markup.replace(TAG_END, ' ' + ReactMarkupChecksum.CHECKSUM_ATTR_NAME + '="' + checksum + '"$&');
  }
}
```
- example usage
```shell
...
    var componentInstance = instantiateReactComponent(element, true);
    var markup = ReactReconciler.mountComponent(componentInstance, transaction, null, ReactDOMContainerInfo(), emptyObject, 0 /*
parentDebugID */
    );
    if (process.env.NODE_ENV !== 'production') {
      ReactInstrumentation.debugTool.onUnmountComponent(componentInstance._debugID);
    }
    if (!makeStaticMarkup) {
      markup = ReactMarkupChecksum.addChecksumToMarkup(markup);
    }
    return markup;
  }, null);
} finally {
  pendingTransactions--;
  ReactServerRenderingTransaction.release(transaction);
  // Revert to the DOM batching strategy since these two renderers
...
```

#### <a name="apidoc.element.react-dom.ReactMarkupChecksum.canReuseMarkup"></a>[function <span class="apidocSignatureSpan">react-dom.ReactMarkupChecksum.</span>canReuseMarkup (markup, element)](#apidoc.element.react-dom.ReactMarkupChecksum.canReuseMarkup)
- description and source-code
```javascript
canReuseMarkup = function (markup, element) {
  var existingChecksum = element.getAttribute(ReactMarkupChecksum.CHECKSUM_ATTR_NAME);
  existingChecksum = existingChecksum && parseInt(existingChecksum, 10);
  var markupChecksum = adler32(markup);
  return markupChecksum === existingChecksum;
}
```
- example usage
```shell
...
  },

  _mountImageIntoNode: function (markup, container, instance, shouldReuseMarkup, transaction) {
    !isValidContainer(container) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'mountComponentIntoNode(...): Target
 container is not valid.') : _prodInvariant('41') : void 0;

    if (shouldReuseMarkup) {
      var rootElement = getReactRootElementInContainer(container);
      if (ReactMarkupChecksum.canReuseMarkup(markup, rootElement)) {
ReactDOMComponentTree.precacheNode(instance, rootElement);
return;
      } else {
var checksum = rootElement.getAttribute(ReactMarkupChecksum.CHECKSUM_ATTR_NAME);
rootElement.removeAttribute(ReactMarkupChecksum.CHECKSUM_ATTR_NAME);

var rootMarkup = rootElement.outerHTML;
...
```



# <a name="apidoc.module.react-dom.ReactMount"></a>[module react-dom.ReactMount](#apidoc.module.react-dom.ReactMount)

#### <a name="apidoc.element.react-dom.ReactMount.TopLevelWrapper"></a>[function <span class="apidocSignatureSpan">react-dom.ReactMount.</span>TopLevelWrapper ()](#apidoc.element.react-dom.ReactMount.TopLevelWrapper)
- description and source-code
```javascript
TopLevelWrapper = function () {
  this.rootID = topLevelRootCounter++;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactMount._mountImageIntoNode"></a>[function <span class="apidocSignatureSpan">react-dom.ReactMount.</span>_mountImageIntoNode (markup, container, instance, shouldReuseMarkup, transaction)](#apidoc.element.react-dom.ReactMount._mountImageIntoNode)
- description and source-code
```javascript
_mountImageIntoNode = function (markup, container, instance, shouldReuseMarkup, transaction) {
  !isValidContainer(container) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'mountComponentIntoNode(...): Target container
 is not valid.') : _prodInvariant('41') : void 0;

  if (shouldReuseMarkup) {
    var rootElement = getReactRootElementInContainer(container);
    if (ReactMarkupChecksum.canReuseMarkup(markup, rootElement)) {
      ReactDOMComponentTree.precacheNode(instance, rootElement);
      return;
    } else {
      var checksum = rootElement.getAttribute(ReactMarkupChecksum.CHECKSUM_ATTR_NAME);
      rootElement.removeAttribute(ReactMarkupChecksum.CHECKSUM_ATTR_NAME);

      var rootMarkup = rootElement.outerHTML;
      rootElement.setAttribute(ReactMarkupChecksum.CHECKSUM_ATTR_NAME, checksum);

      var normalizedMarkup = markup;
      if (process.env.NODE_ENV !== 'production') {
        // because rootMarkup is retrieved from the DOM, various normalizations
        // will have occurred which will not be present in 'markup'. Here,
        // insert markup into a <div> or <iframe> depending on the container
        // type to perform the same normalizations before comparing.
        var normalizer;
        if (container.nodeType === ELEMENT_NODE_TYPE) {
          normalizer = document.createElement('div');
          normalizer.innerHTML = markup;
          normalizedMarkup = normalizer.innerHTML;
        } else {
          normalizer = document.createElement('iframe');
          document.body.appendChild(normalizer);
          normalizer.contentDocument.write(markup);
          normalizedMarkup = normalizer.contentDocument.documentElement.outerHTML;
          document.body.removeChild(normalizer);
        }
      }

      var diffIndex = firstDifferenceIndex(normalizedMarkup, rootMarkup);
      var difference = ' (client) ' + normalizedMarkup.substring(diffIndex - 20, diffIndex + 20) + '\n (server) ' + rootMarkup.substring
(diffIndex - 20, diffIndex + 20);

      !(container.nodeType !== DOC_NODE_TYPE) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'You\'re trying to render
 a component to the document using server rendering but the checksum was invalid. This usually means you rendered a different component
 type or props on the client from the one on the server, or your render() methods are impure. React cannot handle this case due
to cross-browser quirks by rendering at the document root. You should look for environment dependent code in your components and
 ensure the props are the same client and server side:\n%s', difference) : _prodInvariant('42', difference) : void 0;

      if (process.env.NODE_ENV !== 'production') {
        process.env.NODE_ENV !== 'production' ? warning(false, 'React attempted to reuse markup in a container but the ' + 'checksum
 was invalid. This generally means that you are ' + 'using server rendering and the markup generated on the ' + 'server was not
what the client was expecting. React injected ' + 'new markup to compensate which works but you have lost many ' + 'of the benefits
 of server rendering. Instead, figure out ' + 'why the markup being generated is different on the client ' + 'or server:\n%s', difference) : void 0;
      }
    }
  }

  !(container.nodeType !== DOC_NODE_TYPE) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'You\'re trying to render a
 component to the document but you didn\'t use server rendering. We can\'t do this without using server rendering due to cross-browser quirks. See ReactDOMServer.renderToString() for server rendering.') : _prodInvariant('43') : void 0;

  if (transaction.useCreateElement) {
    while (container.lastChild) {
      container.removeChild(container.lastChild);
    }
    DOMLazyTree.insertTreeBefore(container, markup, null);
  } else {
    setInnerHTML(container, markup);
    ReactDOMComponentTree.precacheNode(instance, container.firstChild);
  }

  if (process.env.NODE_ENV !== 'production') {
    var hostNode = ReactDOMComponentTree.getInstanceFromNode(container.firstChild);
    if (hostNode._debugID !== 0) { ...
```
- example usage
```shell
...
 );

 if (markerName) {
   console.timeEnd(markerName);
 }

 wrapperInstance._renderedComponent._topLevelWrapper = wrapperInstance;
 ReactMount._mountImageIntoNode(markup, container, wrapperInstance, shouldReuseMarkup, transaction);
}

/**
* Batched mount.
*
* @param {ReactComponent} componentInstance The instance to mount.
* @param {DOMElement} container DOM element to mount into.
...
```

#### <a name="apidoc.element.react-dom.ReactMount._renderNewRootComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactMount.</span>_renderNewRootComponent (nextElement, container, shouldReuseMarkup, context)](#apidoc.element.react-dom.ReactMount._renderNewRootComponent)
- description and source-code
```javascript
_renderNewRootComponent = function (nextElement, container, shouldReuseMarkup, context) {
  // Various parts of our code (such as ReactCompositeComponent's
  // _renderValidatedComponent) assume that calls to render aren't nested;
  // verify that that's the case.
  process.env.NODE_ENV !== 'production' ? warning(ReactCurrentOwner.current == null, '_renderNewRootComponent(): Render methods
should be a pure function ' + 'of props and state; triggering nested component updates from ' + 'render is not allowed. If necessary
, trigger nested updates in ' + 'componentDidUpdate. Check the render method of %s.', ReactCurrentOwner.current && ReactCurrentOwner
.current.getName() || 'ReactCompositeComponent') : void 0;

  !isValidContainer(container) ? process.env.NODE_ENV !== 'production' ? invariant(false, '_registerComponent(...): Target container
 is not a DOM element.') : _prodInvariant('37') : void 0;

  ReactBrowserEventEmitter.ensureScrollValueMonitoring();
  var componentInstance = instantiateReactComponent(nextElement, false);

  // The initial render is synchronous but any updates that happen during
  // rendering, in componentWillMount or componentDidMount, will be batched
  // according to the current batching strategy.

  ReactUpdates.batchedUpdates(batchedMountComponentIntoNode, componentInstance, container, shouldReuseMarkup, context);

  var wrapperID = componentInstance._instance.rootID;
  instancesByReactRootID[wrapperID] = componentInstance;

  return componentInstance;
}
```
- example usage
```shell
...
        }
        rootElementSibling = rootElementSibling.nextSibling;
      }
    }
  }

  var shouldReuseMarkup = containerHasReactMarkup && !prevComponent && !containerHasNonRootReactChild;
  var component = ReactMount._renderNewRootComponent(nextWrappedElement, container, shouldReuseMarkup, nextContext)._renderedComponent
.getPublicInstance();
  if (callback) {
    callback.call(component);
  }
  return component;
},

/**
...
```

#### <a name="apidoc.element.react-dom.ReactMount._renderSubtreeIntoContainer"></a>[function <span class="apidocSignatureSpan">react-dom.ReactMount.</span>_renderSubtreeIntoContainer (parentComponent, nextElement, container, callback)](#apidoc.element.react-dom.ReactMount._renderSubtreeIntoContainer)
- description and source-code
```javascript
_renderSubtreeIntoContainer = function (parentComponent, nextElement, container, callback) {
  ReactUpdateQueue.validateCallback(callback, 'ReactDOM.render');
  !React.isValidElement(nextElement) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'ReactDOM.render(): Invalid component
 element.%s', typeof nextElement === 'string' ? ' Instead of passing a string like\'div\', pass ' + 'React.createElement(\'div\') or <div />.' : typeof nextElement === 'function' ? ' Instead of passing a class like Foo, pass ' + 'React.createElement(Foo) or <Foo />.' :
  // Check if it quacks like an element
  nextElement != null && nextElement.props !== undefined ? ' This may be caused by unintentionally loading two independent ' + '
copies of React.' : '') : _prodInvariant('39', typeof nextElement === 'string' ? ' Instead of passing a string like\'div\', pass ' + 'React.createElement(\'div\') or <div />.' : typeof nextElement === 'function' ? ' Instead of passing a class like Foo, pass ' + 'React.createElement(Foo) or <Foo />.' : nextElement != null && nextElement.props !== undefined ? ' This may be caused by unintentionally loading two independent ' + 'copies of React.' : '') : void 0;

  process.env.NODE_ENV !== 'production' ? warning(!container || !container.tagName || container.tagName.toUpperCase() !== 'BODY', '
render(): Rendering components directly into document.body is ' + 'discouraged, since its children are often manipulated by third
-party ' + 'scripts and browser extensions. This may lead to subtle ' + 'reconciliation issues. Try rendering into a container element
 created ' + 'for your app.') : void 0;

  var nextWrappedElement = React.createElement(TopLevelWrapper, { child: nextElement });

  var nextContext;
  if (parentComponent) {
    var parentInst = ReactInstanceMap.get(parentComponent);
    nextContext = parentInst._processChildContext(parentInst._context);
  } else {
    nextContext = emptyObject;
  }

  var prevComponent = getTopLevelWrapperInContainer(container);

  if (prevComponent) {
    var prevWrappedElement = prevComponent._currentElement;
    var prevElement = prevWrappedElement.props.child;
    if (shouldUpdateReactComponent(prevElement, nextElement)) {
      var publicInst = prevComponent._renderedComponent.getPublicInstance();
      var updatedCallback = callback && function () {
        callback.call(publicInst);
      };
      ReactMount._updateRootComponent(prevComponent, nextWrappedElement, nextContext, container, updatedCallback);
      return publicInst;
    } else {
      ReactMount.unmountComponentAtNode(container);
    }
  }

  var reactRootElement = getReactRootElementInContainer(container);
  var containerHasReactMarkup = reactRootElement && !!internalGetID(reactRootElement);
  var containerHasNonRootReactChild = hasNonRootReactChild(container);

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(!containerHasNonRootReactChild, 'render(...): Replacing React-rendered children
 with a new root ' + 'component. If you intended to update the children of this node, ' + 'you should instead have the existing
children update their state ' + 'and render the new components instead of calling ReactDOM.render.') : void 0;

    if (!containerHasReactMarkup || reactRootElement.nextSibling) {
      var rootElementSibling = reactRootElement;
      while (rootElementSibling) {
        if (internalGetID(rootElementSibling)) {
          process.env.NODE_ENV !== 'production' ? warning(false, 'render(): Target node has markup rendered by React, but there ' + '
are unrelated nodes as well. This is most commonly caused by ' + 'white-space inserted around server-rendered markup.') : void 0
;
          break;
        }
        rootElementSibling = rootElementSibling.nextSibling;
      }
    }
  }

  var shouldReuseMarkup = containerHasReactMarkup && !prevComponent && !containerHasNonRootReactChild;
  var component = ReactMount._renderNewRootComponent(nextWrappedElement, container, shouldReuseMarkup, nextContext)._renderedComponent
.getPublicInstance();
  if (callback) {
    callback.call(compon ...
```
- example usage
```shell
...
 * @param {ReactElement} nextElement Component element to render.
 * @param {DOMElement} container DOM element to render into.
 * @param {?function} callback function triggered on completion
 * @return {ReactComponent} Component instance rendered in 'container'.
 */
renderSubtreeIntoContainer: function (parentComponent, nextElement, container, callback) {
  !(parentComponent != null && ReactInstanceMap.has(parentComponent)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '
parentComponent must be a valid React Component') : _prodInvariant('38') : void 0;
  return ReactMount._renderSubtreeIntoContainer(parentComponent, nextElement, container, callback);
},

_renderSubtreeIntoContainer: function (parentComponent, nextElement, container, callback) {
  ReactUpdateQueue.validateCallback(callback, 'ReactDOM.render');
  !React.isValidElement(nextElement) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'ReactDOM.render(): Invalid component
 element.%s', typeof nextElement === 'string' ? ' Instead of passing a string like\'div\', pass ' + 'React.createElement(\'div\') or <div />.' : typeof nextElement === 'function' ? ' Instead of passing a class like Foo, pass ' + 'React.createElement(Foo) or <Foo />.' :
  // Check if it quacks like an element
  nextElement != null && nextElement.props !== undefined ? ' This may be caused by unintentionally loading two independent ' + '
copies of React.' : '') : _prodInvariant('39', typeof nextElement === 'string' ? ' Instead of passing a string like\'div\', pass ' + 'React.createElement(\'div\') or <div />.' : typeof nextElement === 'function' ? ' Instead of passing a class like Foo, pass ' + 'React.createElement(Foo) or <Foo />.' : nextElement != null && nextElement.props !== undefined ? ' This may be caused by unintentionally loading two independent ' + 'copies of React.' : '') : void 0;
...
```

#### <a name="apidoc.element.react-dom.ReactMount._updateRootComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactMount.</span>_updateRootComponent (prevComponent, nextElement, nextContext, container, callback)](#apidoc.element.react-dom.ReactMount._updateRootComponent)
- description and source-code
```javascript
_updateRootComponent = function (prevComponent, nextElement, nextContext, container, callback) {
  ReactMount.scrollMonitor(container, function () {
    ReactUpdateQueue.enqueueElementInternal(prevComponent, nextElement, nextContext);
    if (callback) {
      ReactUpdateQueue.enqueueCallbackInternal(prevComponent, callback);
    }
  });

  return prevComponent;
}
```
- example usage
```shell
...
  var prevWrappedElement = prevComponent._currentElement;
  var prevElement = prevWrappedElement.props.child;
  if (shouldUpdateReactComponent(prevElement, nextElement)) {
    var publicInst = prevComponent._renderedComponent.getPublicInstance();
    var updatedCallback = callback && function () {
      callback.call(publicInst);
    };
    ReactMount._updateRootComponent(prevComponent, nextWrappedElement, nextContext, container, updatedCallback);
    return publicInst;
  } else {
    ReactMount.unmountComponentAtNode(container);
  }
}

var reactRootElement = getReactRootElementInContainer(container);
...
```

#### <a name="apidoc.element.react-dom.ReactMount.render"></a>[function <span class="apidocSignatureSpan">react-dom.ReactMount.</span>render (nextElement, container, callback)](#apidoc.element.react-dom.ReactMount.render)
- description and source-code
```javascript
render = function (nextElement, container, callback) {
  return ReactMount._renderSubtreeIntoContainer(null, nextElement, container, callback);
}
```
- example usage
```shell
...

class MyComponent extends React.Component {
  render() {
    return <div>Hello World</div>;
  }
}

ReactDOM.render(<MyComponent />, node);
'''

### On the server

'''js
var React = require('react');
var ReactDOMServer = require('react-dom/server');
...
```

#### <a name="apidoc.element.react-dom.ReactMount.renderSubtreeIntoContainer"></a>[function <span class="apidocSignatureSpan">react-dom.ReactMount.</span>renderSubtreeIntoContainer (parentComponent, nextElement, container, callback)](#apidoc.element.react-dom.ReactMount.renderSubtreeIntoContainer)
- description and source-code
```javascript
renderSubtreeIntoContainer = function (parentComponent, nextElement, container, callback) {
  !(parentComponent != null && ReactInstanceMap.has(parentComponent)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '
parentComponent must be a valid React Component') : _prodInvariant('38') : void 0;
  return ReactMount._renderSubtreeIntoContainer(parentComponent, nextElement, container, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactMount.scrollMonitor"></a>[function <span class="apidocSignatureSpan">react-dom.ReactMount.</span>scrollMonitor (container, renderCallback)](#apidoc.element.react-dom.ReactMount.scrollMonitor)
- description and source-code
```javascript
scrollMonitor = function (container, renderCallback) {
  renderCallback();
}
```
- example usage
```shell
...
   * Take a component that's already mounted into the DOM and replace its props
   * @param {ReactComponent} prevComponent component instance already in the DOM
   * @param {ReactElement} nextElement component instance to render
   * @param {DOMElement} container container to render into
   * @param {?function} callback function triggered on completion
   */
  _updateRootComponent: function (prevComponent, nextElement, nextContext, container, callback) {
ReactMount.scrollMonitor(container, function () {
  ReactUpdateQueue.enqueueElementInternal(prevComponent, nextElement, nextContext);
  if (callback) {
    ReactUpdateQueue.enqueueCallbackInternal(prevComponent, callback);
  }
});

return prevComponent;
...
```

#### <a name="apidoc.element.react-dom.ReactMount.unmountComponentAtNode"></a>[function <span class="apidocSignatureSpan">react-dom.ReactMount.</span>unmountComponentAtNode (container)](#apidoc.element.react-dom.ReactMount.unmountComponentAtNode)
- description and source-code
```javascript
unmountComponentAtNode = function (container) {
  // Various parts of our code (such as ReactCompositeComponent's
  // _renderValidatedComponent) assume that calls to render aren't nested;
  // verify that that's the case. (Strictly speaking, unmounting won't cause a
  // render but we still don't expect to be in a render call here.)
  process.env.NODE_ENV !== 'production' ? warning(ReactCurrentOwner.current == null, 'unmountComponentAtNode(): Render methods should
 be a pure function ' + 'of props and state; triggering nested component updates from render ' + 'is not allowed. If necessary,
trigger nested updates in ' + 'componentDidUpdate. Check the render method of %s.', ReactCurrentOwner.current && ReactCurrentOwner
.current.getName() || 'ReactCompositeComponent') : void 0;

  !isValidContainer(container) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'unmountComponentAtNode(...): Target container
 is not a DOM element.') : _prodInvariant('40') : void 0;

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(!nodeIsRenderedByOtherInstance(container), 'unmountComponentAtNode(): The node
 you\'re attempting to unmount ' + 'was rendered by another copy of React.') : void 0;
  }

  var prevComponent = getTopLevelWrapperInContainer(container);
  if (!prevComponent) {
    // Check if the node being unmounted was rendered by React, but isn't a
    // root node.
    var containerHasNonRootReactChild = hasNonRootReactChild(container);

    // Check if the container itself is a React root node.
    var isContainerReactRoot = container.nodeType === 1 && container.hasAttribute(ROOT_ATTR_NAME);

    if (process.env.NODE_ENV !== 'production') {
      process.env.NODE_ENV !== 'production' ? warning(!containerHasNonRootReactChild, 'unmountComponentAtNode(): The node you\'re
 attempting to unmount ' + 'was rendered by React and is not a top-level container. %s', isContainerReactRoot ? 'You may have accidentally
 passed in a React root node instead ' + 'of its container.' : 'Instead, have the parent component update its state and ' + 'rerender
 in order to remove this component.') : void 0;
    }

    return false;
  }
  delete instancesByReactRootID[prevComponent._instance.rootID];
  ReactUpdates.batchedUpdates(unmountComponentFromNode, prevComponent, container, false);
  return true;
}
```
- example usage
```shell
...
    var publicInst = prevComponent._renderedComponent.getPublicInstance();
    var updatedCallback = callback && function () {
      callback.call(publicInst);
    };
    ReactMount._updateRootComponent(prevComponent, nextWrappedElement, nextContext, container, updatedCallback);
    return publicInst;
  } else {
    ReactMount.unmountComponentAtNode(container);
  }
}

var reactRootElement = getReactRootElementInContainer(container);
var containerHasReactMarkup = reactRootElement && !!internalGetID(reactRootElement);
var containerHasNonRootReactChild = hasNonRootReactChild(container);
...
```



# <a name="apidoc.module.react-dom.ReactNodeTypes"></a>[module react-dom.ReactNodeTypes](#apidoc.module.react-dom.ReactNodeTypes)

#### <a name="apidoc.element.react-dom.ReactNodeTypes.getType"></a>[function <span class="apidocSignatureSpan">react-dom.ReactNodeTypes.</span>getType (node)](#apidoc.element.react-dom.ReactNodeTypes.getType)
- description and source-code
```javascript
getType = function (node) {
  if (node === null || node === false) {
    return ReactNodeTypes.EMPTY;
  } else if (React.isValidElement(node)) {
    if (typeof node.type === 'function') {
      return ReactNodeTypes.COMPOSITE;
    } else {
      return ReactNodeTypes.HOST;
    }
  }
  !false ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Unexpected node: %s', node) : _prodInvariant('26', node) :
void 0;
}
```
- example usage
```shell
...
}

// If not a stateless component, we now render
if (renderedElement === undefined) {
  renderedElement = this._renderValidatedComponent();
}

var nodeType = ReactNodeTypes.getType(renderedElement);
this._renderedNodeType = nodeType;
var child = this._instantiateReactComponent(renderedElement, nodeType !== ReactNodeTypes.EMPTY /* shouldHaveDebugID */
);
this._renderedComponent = child;

var markup = ReactReconciler.mountComponent(child, transaction, hostParent, hostContainerInfo, this._processChildContext(context
), debugID);
...
```



# <a name="apidoc.module.react-dom.ReactOwner"></a>[module react-dom.ReactOwner](#apidoc.module.react-dom.ReactOwner)

#### <a name="apidoc.element.react-dom.ReactOwner.addComponentAsRefTo"></a>[function <span class="apidocSignatureSpan">react-dom.ReactOwner.</span>addComponentAsRefTo (component, ref, owner)](#apidoc.element.react-dom.ReactOwner.addComponentAsRefTo)
- description and source-code
```javascript
addComponentAsRefTo = function (component, ref, owner) {
  !isValidOwner(owner) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'addComponentAsRefTo(...): Only a ReactOwner can
 have refs. You might be adding a ref to a component that was not created inside a component\'s 'render' method, or you have multiple copies of React loaded (details: https://fb.me/react-refs-must-have-owner).') : _prodInvariant('119') : void 0;
  owner.attachRef(ref, component);
}
```
- example usage
```shell
...
var ReactRef = {};

function attachRef(ref, component, owner) {
if (typeof ref === 'function') {
  ref(component.getPublicInstance());
} else {
  // Legacy ref
  ReactOwner.addComponentAsRefTo(component, ref, owner);
}
}

function detachRef(ref, component, owner) {
if (typeof ref === 'function') {
  ref(null);
} else {
...
```

#### <a name="apidoc.element.react-dom.ReactOwner.removeComponentAsRefFrom"></a>[function <span class="apidocSignatureSpan">react-dom.ReactOwner.</span>removeComponentAsRefFrom (component, ref, owner)](#apidoc.element.react-dom.ReactOwner.removeComponentAsRefFrom)
- description and source-code
```javascript
removeComponentAsRefFrom = function (component, ref, owner) {
  !isValidOwner(owner) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'removeComponentAsRefFrom(...): Only a ReactOwner
 can have refs. You might be removing a ref to a component that was not created inside a component\'s 'render' method, or you have multiple copies of React loaded (details: https://fb.me/react-refs-must-have-owner).') : _prodInvariant('120') : void 0;
  var ownerPublicInstance = owner.getPublicInstance();
  // Check that 'component''s owner is still alive and that 'component' is still the current ref
  // because we do not want to detach the ref if another component stole it.
  if (ownerPublicInstance && ownerPublicInstance.refs[ref] === component.getPublicInstance()) {
    owner.detachRef(ref);
  }
}
```
- example usage
```shell
...
}

function detachRef(ref, component, owner) {
if (typeof ref === 'function') {
  ref(null);
} else {
  // Legacy ref
  ReactOwner.removeComponentAsRefFrom(component, ref, owner);
}
}

ReactRef.attachRefs = function (instance, element) {
if (element === null || typeof element !== 'object') {
  return;
}
...
```



# <a name="apidoc.module.react-dom.ReactPerf"></a>[module react-dom.ReactPerf](#apidoc.module.react-dom.ReactPerf)

#### <a name="apidoc.element.react-dom.ReactPerf.getExclusive"></a>[function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>getExclusive ()](#apidoc.element.react-dom.ReactPerf.getExclusive)
- description and source-code
```javascript
function getExclusive() {
  var flushHistory = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : getLastMeasurements();

  if (!(process.env.NODE_ENV !== 'production')) {
    warnInProduction();
    return [];
  }

  var aggregatedStats = {};
  var affectedIDs = {};

  function updateAggregatedStats(treeSnapshot, instanceID, timerType, applyUpdate) {
    var displayName = treeSnapshot[instanceID].displayName;

    var key = displayName;
    var stats = aggregatedStats[key];
    if (!stats) {
      affectedIDs[key] = {};
      stats = aggregatedStats[key] = {
        key: key,
        instanceCount: 0,
        counts: {},
        durations: {},
        totalDuration: 0
      };
    }
    if (!stats.durations[timerType]) {
      stats.durations[timerType] = 0;
    }
    if (!stats.counts[timerType]) {
      stats.counts[timerType] = 0;
    }
    affectedIDs[key][instanceID] = true;
    applyUpdate(stats);
  }

  flushHistory.forEach(function (flush) {
    var measurements = flush.measurements,
        treeSnapshot = flush.treeSnapshot;

    measurements.forEach(function (measurement) {
      var duration = measurement.duration,
          instanceID = measurement.instanceID,
          timerType = measurement.timerType;

      updateAggregatedStats(treeSnapshot, instanceID, timerType, function (stats) {
        stats.totalDuration += duration;
        stats.durations[timerType] += duration;
        stats.counts[timerType]++;
      });
    });
  });

  return Object.keys(aggregatedStats).map(function (key) {
    return _extends({}, aggregatedStats[key], {
      instanceCount: Object.keys(affectedIDs[key]).length
    });
  }).sort(function (a, b) {
    return b.totalDuration - a.totalDuration;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactPerf.getInclusive"></a>[function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>getInclusive ()](#apidoc.element.react-dom.ReactPerf.getInclusive)
- description and source-code
```javascript
function getInclusive() {
  var flushHistory = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : getLastMeasurements();

  if (!(process.env.NODE_ENV !== 'production')) {
    warnInProduction();
    return [];
  }

  var aggregatedStats = {};
  var affectedIDs = {};

  function updateAggregatedStats(treeSnapshot, instanceID, applyUpdate) {
    var _treeSnapshot$instanc = treeSnapshot[instanceID],
        displayName = _treeSnapshot$instanc.displayName,
        ownerID = _treeSnapshot$instanc.ownerID;

    var owner = treeSnapshot[ownerID];
    var key = (owner ? owner.displayName + ' > ' : '') + displayName;
    var stats = aggregatedStats[key];
    if (!stats) {
      affectedIDs[key] = {};
      stats = aggregatedStats[key] = {
        key: key,
        instanceCount: 0,
        inclusiveRenderDuration: 0,
        renderCount: 0
      };
    }
    affectedIDs[key][instanceID] = true;
    applyUpdate(stats);
  }

  var isCompositeByID = {};
  flushHistory.forEach(function (flush) {
    var measurements = flush.measurements;

    measurements.forEach(function (measurement) {
      var instanceID = measurement.instanceID,
          timerType = measurement.timerType;

      if (timerType !== 'render') {
        return;
      }
      isCompositeByID[instanceID] = true;
    });
  });

  flushHistory.forEach(function (flush) {
    var measurements = flush.measurements,
        treeSnapshot = flush.treeSnapshot;

    measurements.forEach(function (measurement) {
      var duration = measurement.duration,
          instanceID = measurement.instanceID,
          timerType = measurement.timerType;

      if (timerType !== 'render') {
        return;
      }
      updateAggregatedStats(treeSnapshot, instanceID, function (stats) {
        stats.renderCount++;
      });
      var nextParentID = instanceID;
      while (nextParentID) {
        // As we traverse parents, only count inclusive time towards composites.
        // We know something is a composite if its render() was called.
        if (isCompositeByID[nextParentID]) {
          updateAggregatedStats(treeSnapshot, nextParentID, function (stats) {
            stats.inclusiveRenderDuration += duration;
          });
        }
        nextParentID = treeSnapshot[nextParentID].parentID;
      }
    });
  });

  return Object.keys(aggregatedStats).map(function (key) {
    return _extends({}, aggregatedStats[key], {
      instanceCount: Object.keys(affectedIDs[key]).length
    });
  }).sort(function (a, b) {
    return b.inclusiveRenderDuration - a.inclusiveRenderDuration;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactPerf.getLastMeasurements"></a>[function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>getLastMeasurements ()](#apidoc.element.react-dom.ReactPerf.getLastMeasurements)
- description and source-code
```javascript
function getLastMeasurements() {
  if (!(process.env.NODE_ENV !== 'production')) {
    warnInProduction();
    return [];
  }

  return ReactDebugTool.getFlushHistory();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactPerf.getMeasurementsSummaryMap"></a>[function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>getMeasurementsSummaryMap (measurements)](#apidoc.element.react-dom.ReactPerf.getMeasurementsSummaryMap)
- description and source-code
```javascript
function getMeasurementsSummaryMap(measurements) {
  process.env.NODE_ENV !== 'production' ? warning(warnedAboutGetMeasurementsSummaryMap, ''ReactPerf.getMeasurementsSummaryMap(...)'
is deprecated. Use ' + ''ReactPerf.getWasted(...)' instead.') : void 0;
  warnedAboutGetMeasurementsSummaryMap = true;
  return getWasted(measurements);
}
```
- example usage
```shell
...
process.env.NODE_ENV !== 'production' ? warning(warnedAboutPrintDOM, ''ReactPerf.printDOM(...)' is deprecated. Use ' + ''ReactPerf
.printOperations(...)' instead.') : void 0;
warnedAboutPrintDOM = true;
return printOperations(measurements);
}

var warnedAboutGetMeasurementsSummaryMap = false;
function getMeasurementsSummaryMap(measurements) {
process.env.NODE_ENV !== 'production' ? warning(warnedAboutGetMeasurementsSummaryMap, ''ReactPerf.getMeasurementsSummaryMap(...)'
is deprecated. Use ' + ''ReactPerf.getWasted(...)' instead.') : void 0;
warnedAboutGetMeasurementsSummaryMap = true;
return getWasted(measurements);
}

function start() {
if (!(process.env.NODE_ENV !== 'production')) {
  warnInProduction();
...
```

#### <a name="apidoc.element.react-dom.ReactPerf.getOperations"></a>[function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>getOperations ()](#apidoc.element.react-dom.ReactPerf.getOperations)
- description and source-code
```javascript
function getOperations() {
  var flushHistory = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : getLastMeasurements();

  if (!(process.env.NODE_ENV !== 'production')) {
    warnInProduction();
    return [];
  }

  var stats = [];
  flushHistory.forEach(function (flush, flushIndex) {
    var operations = flush.operations,
        treeSnapshot = flush.treeSnapshot;

    operations.forEach(function (operation) {
      var instanceID = operation.instanceID,
          type = operation.type,
          payload = operation.payload;
      var _treeSnapshot$instanc3 = treeSnapshot[instanceID],
          displayName = _treeSnapshot$instanc3.displayName,
          ownerID = _treeSnapshot$instanc3.ownerID;

      var owner = treeSnapshot[ownerID];
      var key = (owner ? owner.displayName + ' > ' : '') + displayName;

      stats.push({
        flushIndex: flushIndex,
        instanceID: instanceID,
        key: key,
        type: type,
        ownerID: ownerID,
        payload: payload
      });
    });
  });
  return stats;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactPerf.getWasted"></a>[function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>getWasted ()](#apidoc.element.react-dom.ReactPerf.getWasted)
- description and source-code
```javascript
function getWasted() {
  var flushHistory = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : getLastMeasurements();

  if (!(process.env.NODE_ENV !== 'production')) {
    warnInProduction();
    return [];
  }

  var aggregatedStats = {};
  var affectedIDs = {};

  function updateAggregatedStats(treeSnapshot, instanceID, applyUpdate) {
    var _treeSnapshot$instanc2 = treeSnapshot[instanceID],
        displayName = _treeSnapshot$instanc2.displayName,
        ownerID = _treeSnapshot$instanc2.ownerID;

    var owner = treeSnapshot[ownerID];
    var key = (owner ? owner.displayName + ' > ' : '') + displayName;
    var stats = aggregatedStats[key];
    if (!stats) {
      affectedIDs[key] = {};
      stats = aggregatedStats[key] = {
        key: key,
        instanceCount: 0,
        inclusiveRenderDuration: 0,
        renderCount: 0
      };
    }
    affectedIDs[key][instanceID] = true;
    applyUpdate(stats);
  }

  flushHistory.forEach(function (flush) {
    var measurements = flush.measurements,
        treeSnapshot = flush.treeSnapshot,
        operations = flush.operations;

    var isDefinitelyNotWastedByID = {};

    // Find host components associated with an operation in this batch.
    // Mark all components in their parent tree as definitely not wasted.
    operations.forEach(function (operation) {
      var instanceID = operation.instanceID;

      var nextParentID = instanceID;
      while (nextParentID) {
        isDefinitelyNotWastedByID[nextParentID] = true;
        nextParentID = treeSnapshot[nextParentID].parentID;
      }
    });

    // Find composite components that rendered in this batch.
    // These are potential candidates for being wasted renders.
    var renderedCompositeIDs = {};
    measurements.forEach(function (measurement) {
      var instanceID = measurement.instanceID,
          timerType = measurement.timerType;

      if (timerType !== 'render') {
        return;
      }
      renderedCompositeIDs[instanceID] = true;
    });

    measurements.forEach(function (measurement) {
      var duration = measurement.duration,
          instanceID = measurement.instanceID,
          timerType = measurement.timerType;

      if (timerType !== 'render') {
        return;
      }

      // If there was a DOM update below this component, or it has just been
      // mounted, its render() is not considered wasted.
      var updateCount = treeSnapshot[instanceID].updateCount;

      if (isDefinitelyNotWastedByID[instanceID] || updateCount === 0) {
        return;
      }

      // We consider this render() wasted.
      updateAggregatedStats(treeSnapshot, instanceID, function (stats) {
        stats.renderCount++;
      });

      var nextParentID = instanceID;
      while (nextParentID) {
        // Any parents rendered during this batch are considered wasted
        // unless we previously marked them as dirty.
        var isWasted = renderedCompositeIDs[nextParentID] && !isDefinitelyNotWastedByID[nextParentID];
        if (isWasted) {
          updateAggregatedStats(treeSnapshot, nextParentID, function (stats) {
            stats.inclusiveRenderDuration += duration;
          });
        }
        nextParentID = treeSnapshot[nextParentID].parentID;
      }
    });
  });

  return Object.keys(aggregatedStats).map(function (key) {
    return _extends({}, aggregatedStats[key], {
      instanceCount: Object.keys(affectedIDs[key]).length
    });
  }).sort(function (a, b) {
    return b.inclusiveRenderDuration - a.inclusiveRenderDuration;
  });
}
```
- example usage
```shell
...
process.env.NODE_ENV !== 'production' ? warning(warnedAboutPrintDOM, ''ReactPerf.printDOM(...)' is deprecated. Use ' + ''ReactPerf
.printOperations(...)' instead.') : void 0;
warnedAboutPrintDOM = true;
return printOperations(measurements);
}

var warnedAboutGetMeasurementsSummaryMap = false;
function getMeasurementsSummaryMap(measurements) {
process.env.NODE_ENV !== 'production' ? warning(warnedAboutGetMeasurementsSummaryMap, ''ReactPerf.getMeasurementsSummaryMap(...)'
is deprecated. Use ' + ''ReactPerf.getWasted(...)' instead.') : void 0;
warnedAboutGetMeasurementsSummaryMap = true;
return getWasted(measurements);
}

function start() {
if (!(process.env.NODE_ENV !== 'production')) {
  warnInProduction();
...
```

#### <a name="apidoc.element.react-dom.ReactPerf.isRunning"></a>[function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>isRunning ()](#apidoc.element.react-dom.ReactPerf.isRunning)
- description and source-code
```javascript
function isRunning() {
  if (!(process.env.NODE_ENV !== 'production')) {
    warnInProduction();
    return false;
  }

  return ReactDebugTool.isProfiling();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactPerf.printDOM"></a>[function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>printDOM (measurements)](#apidoc.element.react-dom.ReactPerf.printDOM)
- description and source-code
```javascript
function printDOM(measurements) {
  process.env.NODE_ENV !== 'production' ? warning(warnedAboutPrintDOM, ''ReactPerf.printDOM(...)' is deprecated. Use ' + ''ReactPerf
.printOperations(...)' instead.') : void 0;
  warnedAboutPrintDOM = true;
  return printOperations(measurements);
}
```
- example usage
```shell
...
  };
});
consoleTable(table);
}

var warnedAboutPrintDOM = false;
function printDOM(measurements) {
process.env.NODE_ENV !== 'production' ? warning(warnedAboutPrintDOM, ''ReactPerf.printDOM(...)' is deprecated. Use ' + ''ReactPerf
.printOperations(...)' instead.') : void 0;
warnedAboutPrintDOM = true;
return printOperations(measurements);
}

var warnedAboutGetMeasurementsSummaryMap = false;
function getMeasurementsSummaryMap(measurements) {
process.env.NODE_ENV !== 'production' ? warning(warnedAboutGetMeasurementsSummaryMap, ''ReactPerf.getMeasurementsSummaryMap(...)'
is deprecated. Use ' + ''ReactPerf.getWasted(...)' instead.') : void 0;
...
```

#### <a name="apidoc.element.react-dom.ReactPerf.printExclusive"></a>[function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>printExclusive (flushHistory)](#apidoc.element.react-dom.ReactPerf.printExclusive)
- description and source-code
```javascript
function printExclusive(flushHistory) {
  if (!(process.env.NODE_ENV !== 'production')) {
    warnInProduction();
    return;
  }

  var stats = getExclusive(flushHistory);
  var table = stats.map(function (item) {
    var key = item.key,
        instanceCount = item.instanceCount,
        totalDuration = item.totalDuration;

    var renderCount = item.counts.render || 0;
    var renderDuration = item.durations.render || 0;
    return {
      'Component': key,
      'Total time (ms)': roundFloat(totalDuration),
      'Instance count': instanceCount,
      'Total render time (ms)': roundFloat(renderDuration),
      'Average render time (ms)': renderCount ? roundFloat(renderDuration / renderCount) : undefined,
      'Render count': renderCount,
      'Total lifecycle time (ms)': roundFloat(totalDuration - renderDuration)
    };
  });
  consoleTable(table);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactPerf.printInclusive"></a>[function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>printInclusive (flushHistory)](#apidoc.element.react-dom.ReactPerf.printInclusive)
- description and source-code
```javascript
function printInclusive(flushHistory) {
  if (!(process.env.NODE_ENV !== 'production')) {
    warnInProduction();
    return;
  }

  var stats = getInclusive(flushHistory);
  var table = stats.map(function (item) {
    var key = item.key,
        instanceCount = item.instanceCount,
        inclusiveRenderDuration = item.inclusiveRenderDuration,
        renderCount = item.renderCount;

    return {
      'Owner > Component': key,
      'Inclusive render time (ms)': roundFloat(inclusiveRenderDuration),
      'Instance count': instanceCount,
      'Render count': renderCount
    };
  });
  consoleTable(table);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactPerf.printOperations"></a>[function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>printOperations (flushHistory)](#apidoc.element.react-dom.ReactPerf.printOperations)
- description and source-code
```javascript
function printOperations(flushHistory) {
  if (!(process.env.NODE_ENV !== 'production')) {
    warnInProduction();
    return;
  }

  var stats = getOperations(flushHistory);
  var table = stats.map(function (stat) {
    return {
      'Owner > Node': stat.key,
      'Operation': stat.type,
      'Payload': typeof stat.payload === 'object' ? JSON.stringify(stat.payload) : stat.payload,
      'Flush index': stat.flushIndex,
      'Owner Component ID': stat.ownerID,
      'DOM Component ID': stat.instanceID
    };
  });
  consoleTable(table);
}
```
- example usage
```shell
...
  };
});
consoleTable(table);
}

var warnedAboutPrintDOM = false;
function printDOM(measurements) {
process.env.NODE_ENV !== 'production' ? warning(warnedAboutPrintDOM, ''ReactPerf.printDOM(...)' is deprecated. Use ' + ''ReactPerf
.printOperations(...)' instead.') : void 0;
warnedAboutPrintDOM = true;
return printOperations(measurements);
}

var warnedAboutGetMeasurementsSummaryMap = false;
function getMeasurementsSummaryMap(measurements) {
process.env.NODE_ENV !== 'production' ? warning(warnedAboutGetMeasurementsSummaryMap, ''ReactPerf.getMeasurementsSummaryMap(...)'
is deprecated. Use ' + ''ReactPerf.getWasted(...)' instead.') : void 0;
...
```

#### <a name="apidoc.element.react-dom.ReactPerf.printWasted"></a>[function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>printWasted (flushHistory)](#apidoc.element.react-dom.ReactPerf.printWasted)
- description and source-code
```javascript
function printWasted(flushHistory) {
  if (!(process.env.NODE_ENV !== 'production')) {
    warnInProduction();
    return;
  }

  var stats = getWasted(flushHistory);
  var table = stats.map(function (item) {
    var key = item.key,
        instanceCount = item.instanceCount,
        inclusiveRenderDuration = item.inclusiveRenderDuration,
        renderCount = item.renderCount;

    return {
      'Owner > Component': key,
      'Inclusive wasted time (ms)': roundFloat(inclusiveRenderDuration),
      'Instance count': instanceCount,
      'Render count': renderCount
    };
  });
  consoleTable(table);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactPerf.start"></a>[function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>start ()](#apidoc.element.react-dom.ReactPerf.start)
- description and source-code
```javascript
function start() {
  if (!(process.env.NODE_ENV !== 'production')) {
    warnInProduction();
    return;
  }

  ReactDebugTool.beginProfiling();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactPerf.stop"></a>[function <span class="apidocSignatureSpan">react-dom.ReactPerf.</span>stop ()](#apidoc.element.react-dom.ReactPerf.stop)
- description and source-code
```javascript
function stop() {
  if (!(process.env.NODE_ENV !== 'production')) {
    warnInProduction();
    return;
  }

  ReactDebugTool.endProfiling();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactReconcileTransaction"></a>[module react-dom.ReactReconcileTransaction](#apidoc.module.react-dom.ReactReconcileTransaction)

#### <a name="apidoc.element.react-dom.ReactReconcileTransaction.ReactReconcileTransaction"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ReactReconcileTransaction (useCreateElement)](#apidoc.element.react-dom.ReactReconcileTransaction.ReactReconcileTransaction)
- description and source-code
```javascript
function ReactReconcileTransaction(useCreateElement) {
  this.reinitializeTransaction();
  // Only server-side rendering really needs this option (see
  // 'ReactServerRendering'), but server-side uses
  // 'ReactServerRenderingTransaction' instead. This option is here so that it's
  // accessible and defaults to false when 'ReactDOMComponent' and
  // 'ReactDOMTextComponent' checks it in 'mountComponent'.'
  this.renderToStaticMarkup = false;
  this.reactMountReady = CallbackQueue.getPooled(null);
  this.useCreateElement = useCreateElement;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactReconcileTransaction.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.</span>getPooled (copyFieldsFrom)](#apidoc.element.react-dom.ReactReconcileTransaction.getPooled)
- description and source-code
```javascript
getPooled = function (copyFieldsFrom) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, copyFieldsFrom);
    return instance;
  } else {
    return new Klass(copyFieldsFrom);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.ReactReconcileTransaction.release"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.</span>release (instance)](#apidoc.element.react-dom.ReactReconcileTransaction.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.ReactReconcileTransaction.prototype"></a>[module react-dom.ReactReconcileTransaction.prototype](#apidoc.module.react-dom.ReactReconcileTransaction.prototype)

#### <a name="apidoc.element.react-dom.ReactReconcileTransaction.prototype.checkpoint"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>checkpoint ()](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.checkpoint)
- description and source-code
```javascript
checkpoint = function () {
  // reactMountReady is the our only stateful wrapper
  return this.reactMountReady.checkpoint();
}
```
- example usage
```shell
...
  } else {
    return Component(publicProps, publicContext, updateQueue);
  }
},

performInitialMountWithErrorHandling: function (renderedElement, hostParent, hostContainerInfo, transaction, context) {
  var markup;
  var checkpoint = transaction.checkpoint();
  try {
    markup = this.performInitialMount(renderedElement, hostParent, hostContainerInfo, transaction, context);
  } catch (e) {
    // Roll back to checkpoint, handle error (which may add items to the transaction), and take a new checkpoint
    transaction.rollback(checkpoint);
    this._instance.unstable_handleError(e);
    if (this._pendingStateQueue) {
...
```

#### <a name="apidoc.element.react-dom.ReactReconcileTransaction.prototype.closeAll"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>closeAll (startIndex)](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.closeAll)
- description and source-code
```javascript
closeAll = function (startIndex) {
  !this.isInTransaction() ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Transaction.closeAll(): Cannot close transaction
 when none are open.') : _prodInvariant('28') : void 0;
  var transactionWrappers = this.transactionWrappers;
  for (var i = startIndex; i < transactionWrappers.length; i++) {
    var wrapper = transactionWrappers[i];
    var initData = this.wrapperInitData[i];
    var errorThrown;
    try {
      // Catching errors makes debugging more difficult, so we start with
      // errorThrown set to true before setting it to false after calling
      // close -- if it's still set to true in the finally block, it means
      // wrapper.close threw.
      errorThrown = true;
      if (initData !== OBSERVED_ERROR && wrapper.close) {
        wrapper.close.call(this, initData);
      }
      errorThrown = false;
    } finally {
      if (errorThrown) {
        // The closer for wrapper i threw an error; close the remaining
        // wrappers but silence any exceptions from them to ensure that the
        // first error is the one to bubble up.
        try {
          this.closeAll(i + 1);
        } catch (e) {}
      }
    }
  }
  this.wrapperInitData.length = 0;
}
```
- example usage
```shell
...
  errorThrown = false;
} finally {
  try {
    if (errorThrown) {
      // If 'method' throws, prefer to show that stack trace over any thrown
      // by invoking 'closeAll'.
      try {
        this.closeAll(0);
      } catch (err) {}
    } else {
      // Since 'method' didn't throw, we don't want to silence the exception
      // here.
      this.closeAll(0);
    }
  } finally {
...
```

#### <a name="apidoc.element.react-dom.ReactReconcileTransaction.prototype.destructor"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>destructor ()](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.destructor)
- description and source-code
```javascript
destructor = function () {
  CallbackQueue.release(this.reactMountReady);
  this.reactMountReady = null;
}
```
- example usage
```shell
...
    return new Klass(a1, a2, a3, a4);
  }
};

var standardReleaser = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
};

var DEFAULT_POOL_SIZE = 10;
var DEFAULT_POOLER = oneArgumentPooler;
...
```

#### <a name="apidoc.element.react-dom.ReactReconcileTransaction.prototype.getReactMountReady"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>getReactMountReady ()](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.getReactMountReady)
- description and source-code
```javascript
getReactMountReady = function () {
  return this.reactMountReady;
}
```
- example usage
```shell
...
  markup = this.performInitialMountWithErrorHandling(renderedElement, hostParent, hostContainerInfo, transaction, context);
} else {
  markup = this.performInitialMount(renderedElement, hostParent, hostContainerInfo, transaction, context);
}

if (inst.componentDidMount) {
  if (process.env.NODE_ENV !== 'production') {
    transaction.getReactMountReady().enqueue(function () {
      measureLifeCyclePerf(function () {
        return inst.componentDidMount();
      }, _this._debugID, 'componentDidMount');
    });
  } else {
    transaction.getReactMountReady().enqueue(inst.componentDidMount, inst);
  }
...
```

#### <a name="apidoc.element.react-dom.ReactReconcileTransaction.prototype.getTransactionWrappers"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>getTransactionWrappers ()](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.getTransactionWrappers)
- description and source-code
```javascript
getTransactionWrappers = function () {
  return TRANSACTION_WRAPPERS;
}
```
- example usage
```shell
...
 * Sets up this instance so that it is prepared for collecting metrics. Does
 * so such that this setup method may be used on an instance that is already
 * initialized, in a way that does not consume additional memory upon reuse.
 * That can be useful if you decide to make your subclass of this mixin a
 * "PooledClass".
 */
reinitializeTransaction: function () {
  this.transactionWrappers = this.getTransactionWrappers();
  if (this.wrapperInitData) {
    this.wrapperInitData.length = 0;
  } else {
    this.wrapperInitData = [];
  }
  this._isInTransaction = false;
},
...
```

#### <a name="apidoc.element.react-dom.ReactReconcileTransaction.prototype.getUpdateQueue"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>getUpdateQueue ()](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.getUpdateQueue)
- description and source-code
```javascript
getUpdateQueue = function () {
  return ReactUpdateQueue;
}
```
- example usage
```shell
...
this._hostContainerInfo = hostContainerInfo;

var publicProps = this._currentElement.props;
var publicContext = this._processContext(context);

var Component = this._currentElement.type;

var updateQueue = transaction.getUpdateQueue();

// Initialize the public class
var doConstruct = shouldConstruct(Component);
var inst = this._constructComponent(doConstruct, publicProps, publicContext, updateQueue);
var renderedElement;

// Support functional components
...
```

#### <a name="apidoc.element.react-dom.ReactReconcileTransaction.prototype.initializeAll"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>initializeAll (startIndex)](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.initializeAll)
- description and source-code
```javascript
initializeAll = function (startIndex) {
  var transactionWrappers = this.transactionWrappers;
  for (var i = startIndex; i < transactionWrappers.length; i++) {
    var wrapper = transactionWrappers[i];
    try {
      // Catching errors makes debugging more difficult, so we start with the
      // OBSERVED_ERROR state before overwriting it with the real return value
      // of initialize -- if it's still set to OBSERVED_ERROR in the finally
      // block, it means wrapper.initialize threw.
      this.wrapperInitData[i] = OBSERVED_ERROR;
      this.wrapperInitData[i] = wrapper.initialize ? wrapper.initialize.call(this) : null;
    } finally {
      if (this.wrapperInitData[i] === OBSERVED_ERROR) {
        // The initializer for wrapper i threw an error; initialize the
        // remaining wrappers but silence any exceptions from them to ensure
        // that the first error is the one to bubble up.
        try {
          this.initializeAll(i + 1);
        } catch (err) {}
      }
    }
  }
}
```
- example usage
```shell
...
try {
  this._isInTransaction = true;
  // Catching errors makes debugging more difficult, so we start with
  // errorThrown set to true before setting it to false after calling
  // close -- if it's still set to true in the finally block, it means
  // one of these calls threw.
  errorThrown = true;
  this.initializeAll(0);
  ret = method.call(scope, a, b, c, d, e, f);
  errorThrown = false;
} finally {
  try {
    if (errorThrown) {
      // If 'method' throws, prefer to show that stack trace over any thrown
      // by invoking 'closeAll'.
...
```

#### <a name="apidoc.element.react-dom.ReactReconcileTransaction.prototype.isInTransaction"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>isInTransaction ()](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.isInTransaction)
- description and source-code
```javascript
isInTransaction = function () {
  return !!this._isInTransaction;
}
```
- example usage
```shell
...
 * @param {ReactClass} publicInstance The instance to use as 'this' context.
 * @param {?function} callback Called after state is updated.
 * @internal
 */


ReactServerUpdateQueue.prototype.enqueueCallback = function enqueueCallback(publicInstance, callback, callerName) {
  if (this.transaction.isInTransaction()) {
    ReactUpdateQueue.enqueueCallback(publicInstance, callback, callerName);
  }
};

/**
 * Forces an update. This should only be invoked when it is known with
 * certainty that we are **not** in a DOM transaction.
...
```

#### <a name="apidoc.element.react-dom.ReactReconcileTransaction.prototype.perform"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>perform (method, scope, a, b, c, d, e, f)](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.perform)
- description and source-code
```javascript
perform = function (method, scope, a, b, c, d, e, f) {
  !!this.isInTransaction() ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Transaction.perform(...): Cannot initialize
 a transaction when there is already an outstanding transaction.') : _prodInvariant('27') : void 0;
  var errorThrown;
  var ret;
  try {
    this._isInTransaction = true;
    // Catching errors makes debugging more difficult, so we start with
    // errorThrown set to true before setting it to false after calling
    // close -- if it's still set to true in the finally block, it means
    // one of these calls threw.
    errorThrown = true;
    this.initializeAll(0);
    ret = method.call(scope, a, b, c, d, e, f);
    errorThrown = false;
  } finally {
    try {
      if (errorThrown) {
        // If 'method' throws, prefer to show that stack trace over any thrown
        // by invoking 'closeAll'.
        try {
          this.closeAll(0);
        } catch (err) {}
      } else {
        // Since 'method' didn't throw, we don't want to silence the exception
        // here.
        this.closeAll(0);
      }
    } finally {
      this._isInTransaction = false;
    }
  }
  return ret;
}
```
- example usage
```shell
...

    ReactDefaultBatchingStrategy.isBatchingUpdates = true;

    // The code is written this way to avoid extra allocations
    if (alreadyBatchingUpdates) {
      return callback(a, b, c, d, e);
    } else {
      return transaction.perform(callback, null, a, b, c, d, e);
    }
  }
};

module.exports = ReactDefaultBatchingStrategy;
...
```

#### <a name="apidoc.element.react-dom.ReactReconcileTransaction.prototype.reinitializeTransaction"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>reinitializeTransaction ()](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.reinitializeTransaction)
- description and source-code
```javascript
reinitializeTransaction = function () {
  this.transactionWrappers = this.getTransactionWrappers();
  if (this.wrapperInitData) {
    this.wrapperInitData.length = 0;
  } else {
    this.wrapperInitData = [];
  }
  this._isInTransaction = false;
}
```
- example usage
```shell
...
  initialize: emptyFunction,
  close: ReactUpdates.flushBatchedUpdates.bind(ReactUpdates)
};

var TRANSACTION_WRAPPERS = [FLUSH_BATCHED_UPDATES, RESET_BATCHED_UPDATES];

function ReactDefaultBatchingStrategyTransaction() {
  this.reinitializeTransaction();
}

_assign(ReactDefaultBatchingStrategyTransaction.prototype, Transaction, {
  getTransactionWrappers: function () {
    return TRANSACTION_WRAPPERS;
  }
});
...
```

#### <a name="apidoc.element.react-dom.ReactReconcileTransaction.prototype.rollback"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReconcileTransaction.prototype.</span>rollback (checkpoint)](#apidoc.element.react-dom.ReactReconcileTransaction.prototype.rollback)
- description and source-code
```javascript
rollback = function (checkpoint) {
  this.reactMountReady.rollback(checkpoint);
}
```
- example usage
```shell
...
  performInitialMountWithErrorHandling: function (renderedElement, hostParent, hostContainerInfo, transaction, context) {
    var markup;
    var checkpoint = transaction.checkpoint();
    try {
markup = this.performInitialMount(renderedElement, hostParent, hostContainerInfo, transaction, context);
    } catch (e) {
// Roll back to checkpoint, handle error (which may add items to the transaction), and take a new checkpoint
transaction.rollback(checkpoint);
this._instance.unstable_handleError(e);
if (this._pendingStateQueue) {
  this._instance.state = this._processPendingState(this._instance.props, this._instance.context);
}
checkpoint = transaction.checkpoint();

this._renderedComponent.unmountComponent(true);
...
```



# <a name="apidoc.module.react-dom.ReactReconciler"></a>[module react-dom.ReactReconciler](#apidoc.module.react-dom.ReactReconciler)

#### <a name="apidoc.element.react-dom.ReactReconciler.getHostNode"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReconciler.</span>getHostNode (internalInstance)](#apidoc.element.react-dom.ReactReconciler.getHostNode)
- description and source-code
```javascript
getHostNode = function (internalInstance) {
  return internalInstance.getHostNode();
}
```
- example usage
```shell
...
var prevElement = prevChild && prevChild._currentElement;
var nextElement = nextChildren[name];
if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
  ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
  nextChildren[name] = prevChild;
} else {
  if (prevChild) {
    removedNodes[name] = ReactReconciler.getHostNode(prevChild);
    ReactReconciler.unmountComponent(prevChild, false);
  }
  // The child must be instantiated before it's mounted.
  var nextChildInstance = instantiateReactComponent(nextElement, true);
  nextChildren[name] = nextChildInstance;
  // Creating mount image now ensures refs are resolved in right order
  // (see https://github.com/facebook/react/pull/7101 for explanation).
...
```

#### <a name="apidoc.element.react-dom.ReactReconciler.mountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReconciler.</span>mountComponent (internalInstance, transaction, hostParent, hostContainerInfo, context, parentDebugID // 0 in production and for roots )](#apidoc.element.react-dom.ReactReconciler.mountComponent)
- description and source-code
```javascript
mountComponent = function (internalInstance, transaction, hostParent, hostContainerInfo, context, parentDebugID // 0 in production and for roots ) {
  if (process.env.NODE_ENV !== 'production') {
    if (internalInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onBeforeMountComponent(internalInstance._debugID, internalInstance._currentElement, parentDebugID
);
    }
  }
  var markup = internalInstance.mountComponent(transaction, hostParent, hostContainerInfo, context, parentDebugID);
  if (internalInstance._currentElement && internalInstance._currentElement.ref != null) {
    transaction.getReactMountReady().enqueue(attachRefs, internalInstance);
  }
  if (process.env.NODE_ENV !== 'production') {
    if (internalInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onMountComponent(internalInstance._debugID);
    }
  }
  return markup;
}
```
- example usage
```shell
...
      ReactReconciler.unmountComponent(prevChild, false);
    }
    // The child must be instantiated before it's mounted.
    var nextChildInstance = instantiateReactComponent(nextElement, true);
    nextChildren[name] = nextChildInstance;
    // Creating mount image now ensures refs are resolved in right order
    // (see https://github.com/facebook/react/pull/7101 for explanation).
    var nextChildMountImage = ReactReconciler.mountComponent(nextChildInstance, transaction, hostParent, hostContainerInfo, context
, selfDebugID);
    mountImages.push(nextChildMountImage);
  }
}
// Unmount children that are no longer present.
for (name in prevChildren) {
  if (prevChildren.hasOwnProperty(name) && !(nextChildren && nextChildren.hasOwnProperty(name))) {
    prevChild = prevChildren[name];
...
```

#### <a name="apidoc.element.react-dom.ReactReconciler.performUpdateIfNecessary"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReconciler.</span>performUpdateIfNecessary (internalInstance, transaction, updateBatchNumber)](#apidoc.element.react-dom.ReactReconciler.performUpdateIfNecessary)
- description and source-code
```javascript
performUpdateIfNecessary = function (internalInstance, transaction, updateBatchNumber) {
  if (internalInstance._updateBatchNumber !== updateBatchNumber) {
    // The component's enqueued batch number should always be the current
    // batch or the following one.
    process.env.NODE_ENV !== 'production' ? warning(internalInstance._updateBatchNumber == null || internalInstance._updateBatchNumber
 === updateBatchNumber + 1, 'performUpdateIfNecessary: Unexpected batch number (current %s, ' + 'pending %s)', updateBatchNumber
, internalInstance._updateBatchNumber) : void 0;
    return;
  }
  if (process.env.NODE_ENV !== 'production') {
    if (internalInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onBeforeUpdateComponent(internalInstance._debugID, internalInstance._currentElement);
    }
  }
  internalInstance.performUpdateIfNecessary(transaction);
  if (process.env.NODE_ENV !== 'production') {
    if (internalInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onUpdateComponent(internalInstance._debugID);
    }
  }
}
```
- example usage
```shell
...
    return;
  }
  if (process.env.NODE_ENV !== 'production') {
    if (internalInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onBeforeUpdateComponent(internalInstance._debugID, internalInstance._currentElement);
    }
  }
  internalInstance.performUpdateIfNecessary(transaction);
  if (process.env.NODE_ENV !== 'production') {
    if (internalInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onUpdateComponent(internalInstance._debugID);
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.ReactReconciler.receiveComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReconciler.</span>receiveComponent (internalInstance, nextElement, transaction, context)](#apidoc.element.react-dom.ReactReconciler.receiveComponent)
- description and source-code
```javascript
receiveComponent = function (internalInstance, nextElement, transaction, context) {
  var prevElement = internalInstance._currentElement;

  if (nextElement === prevElement && context === internalInstance._context) {
    // Since elements are immutable after the owner is rendered,
    // we can do a cheap identity compare here to determine if this is a
    // superfluous reconcile. It's possible for state to be mutable but such
    // change should trigger an update of the owner which would recreate
    // the element. We explicitly check for the existence of an owner since
    // it's possible for an element created outside a composite to be
    // deeply mutated and reused.

    // TODO: Bailing out early is just a perf optimization right?
    // TODO: Removing the return statement should affect correctness?
    return;
  }

  if (process.env.NODE_ENV !== 'production') {
    if (internalInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onBeforeUpdateComponent(internalInstance._debugID, nextElement);
    }
  }

  var refsChanged = ReactRef.shouldUpdateRefs(prevElement, nextElement);

  if (refsChanged) {
    ReactRef.detachRefs(internalInstance, prevElement);
  }

  internalInstance.receiveComponent(nextElement, transaction, context);

  if (refsChanged && internalInstance._currentElement && internalInstance._currentElement.ref != null) {
    transaction.getReactMountReady().enqueue(attachRefs, internalInstance);
  }

  if (process.env.NODE_ENV !== 'production') {
    if (internalInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onUpdateComponent(internalInstance._debugID);
    }
  }
}
```
- example usage
```shell
...
if (!nextChildren.hasOwnProperty(name)) {
  continue;
}
prevChild = prevChildren && prevChildren[name];
var prevElement = prevChild && prevChild._currentElement;
var nextElement = nextChildren[name];
if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
  ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
  nextChildren[name] = prevChild;
} else {
  if (prevChild) {
    removedNodes[name] = ReactReconciler.getHostNode(prevChild);
    ReactReconciler.unmountComponent(prevChild, false);
  }
  // The child must be instantiated before it's mounted.
...
```

#### <a name="apidoc.element.react-dom.ReactReconciler.unmountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReconciler.</span>unmountComponent (internalInstance, safely)](#apidoc.element.react-dom.ReactReconciler.unmountComponent)
- description and source-code
```javascript
unmountComponent = function (internalInstance, safely) {
  if (process.env.NODE_ENV !== 'production') {
    if (internalInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onBeforeUnmountComponent(internalInstance._debugID);
    }
  }
  ReactRef.detachRefs(internalInstance, internalInstance._currentElement);
  internalInstance.unmountComponent(safely);
  if (process.env.NODE_ENV !== 'production') {
    if (internalInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onUnmountComponent(internalInstance._debugID);
    }
  }
}
```
- example usage
```shell
...
var nextElement = nextChildren[name];
if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
  ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
  nextChildren[name] = prevChild;
} else {
  if (prevChild) {
    removedNodes[name] = ReactReconciler.getHostNode(prevChild);
    ReactReconciler.unmountComponent(prevChild, false);
  }
  // The child must be instantiated before it's mounted.
  var nextChildInstance = instantiateReactComponent(nextElement, true);
  nextChildren[name] = nextChildInstance;
  // Creating mount image now ensures refs are resolved in right order
  // (see https://github.com/facebook/react/pull/7101 for explanation).
  var nextChildMountImage = ReactReconciler.mountComponent(nextChildInstance, transaction, hostParent, hostContainerInfo, context
, selfDebugID);
...
```



# <a name="apidoc.module.react-dom.ReactRef"></a>[module react-dom.ReactRef](#apidoc.module.react-dom.ReactRef)

#### <a name="apidoc.element.react-dom.ReactRef.attachRefs"></a>[function <span class="apidocSignatureSpan">react-dom.ReactRef.</span>attachRefs (instance, element)](#apidoc.element.react-dom.ReactRef.attachRefs)
- description and source-code
```javascript
attachRefs = function (instance, element) {
  if (element === null || typeof element !== 'object') {
    return;
  }
  var ref = element.ref;
  if (ref != null) {
    attachRef(ref, instance, element._owner);
  }
}
```
- example usage
```shell
...
var warning = require('fbjs/lib/warning');

/**
 * Helper to call ReactRef.attachRefs with this composite component, split out
 * to avoid allocations in the transaction mount-ready queue.
 */
function attachRefs() {
ReactRef.attachRefs(this, this._currentElement);
}

var ReactReconciler = {

/**
 * Initializes the component, renders markup, and registers event listeners.
 *
...
```

#### <a name="apidoc.element.react-dom.ReactRef.detachRefs"></a>[function <span class="apidocSignatureSpan">react-dom.ReactRef.</span>detachRefs (instance, element)](#apidoc.element.react-dom.ReactRef.detachRefs)
- description and source-code
```javascript
detachRefs = function (instance, element) {
  if (element === null || typeof element !== 'object') {
    return;
  }
  var ref = element.ref;
  if (ref != null) {
    detachRef(ref, instance, element._owner);
  }
}
```
- example usage
```shell
...
 */
unmountComponent: function (internalInstance, safely) {
  if (process.env.NODE_ENV !== 'production') {
    if (internalInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onBeforeUnmountComponent(internalInstance._debugID);
    }
  }
  ReactRef.detachRefs(internalInstance, internalInstance._currentElement);
  internalInstance.unmountComponent(safely);
  if (process.env.NODE_ENV !== 'production') {
    if (internalInstance._debugID !== 0) {
      ReactInstrumentation.debugTool.onUnmountComponent(internalInstance._debugID);
    }
  }
},
...
```

#### <a name="apidoc.element.react-dom.ReactRef.shouldUpdateRefs"></a>[function <span class="apidocSignatureSpan">react-dom.ReactRef.</span>shouldUpdateRefs (prevElement, nextElement)](#apidoc.element.react-dom.ReactRef.shouldUpdateRefs)
- description and source-code
```javascript
shouldUpdateRefs = function (prevElement, nextElement) {
  // If either the owner or a 'ref' has changed, make sure the newest owner
  // has stored a reference to 'this', and the previous owner (if different)
  // has forgotten the reference to 'this'. We use the element instead
  // of the public this.props because the post processing cannot determine
  // a ref. The ref conceptually lives on the element.

  // TODO: Should this even be possible? The owner cannot change because
  // it's forbidden by shouldUpdateReactComponent. The ref can change
  // if you swap the keys of but not the refs. Reconsider where this check
  // is made. It probably belongs where the key checking and
  // instantiateReactComponent is done.

  var prevRef = null;
  var prevOwner = null;
  if (prevElement !== null && typeof prevElement === 'object') {
    prevRef = prevElement.ref;
    prevOwner = prevElement._owner;
  }

  var nextRef = null;
  var nextOwner = null;
  if (nextElement !== null && typeof nextElement === 'object') {
    nextRef = nextElement.ref;
    nextOwner = nextElement._owner;
  }

  return prevRef !== nextRef ||
  // If owner changes but we have an unchanged function ref, don't update refs
  typeof nextRef === 'string' && nextOwner !== prevOwner;
}
```
- example usage
```shell
...

if (process.env.NODE_ENV !== 'production') {
  if (internalInstance._debugID !== 0) {
    ReactInstrumentation.debugTool.onBeforeUpdateComponent(internalInstance._debugID, nextElement);
  }
}

var refsChanged = ReactRef.shouldUpdateRefs(prevElement, nextElement);

if (refsChanged) {
  ReactRef.detachRefs(internalInstance, prevElement);
}

internalInstance.receiveComponent(nextElement, transaction, context);
...
```



# <a name="apidoc.module.react-dom.ReactReifiedYield"></a>[module react-dom.ReactReifiedYield](#apidoc.module.react-dom.ReactReifiedYield)

#### <a name="apidoc.element.react-dom.ReactReifiedYield.createReifiedYield"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReifiedYield.</span>createReifiedYield (yieldNode)](#apidoc.element.react-dom.ReactReifiedYield.createReifiedYield)
- description and source-code
```javascript
createReifiedYield = function (yieldNode) {
  var fiber = createFiberFromElementType(yieldNode.continuation, yieldNode.key);
  return {
    continuation: fiber,
    props: yieldNode.props
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactReifiedYield.createUpdatedReifiedYield"></a>[function <span class="apidocSignatureSpan">react-dom.ReactReifiedYield.</span>createUpdatedReifiedYield (previousYield, yieldNode)](#apidoc.element.react-dom.ReactReifiedYield.createUpdatedReifiedYield)
- description and source-code
```javascript
createUpdatedReifiedYield = function (previousYield, yieldNode) {
  return {
    continuation: previousYield.continuation,
    props: yieldNode.props
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactServerBatchingStrategy"></a>[module react-dom.ReactServerBatchingStrategy](#apidoc.module.react-dom.ReactServerBatchingStrategy)

#### <a name="apidoc.element.react-dom.ReactServerBatchingStrategy.batchedUpdates"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerBatchingStrategy.</span>batchedUpdates (callback)](#apidoc.element.react-dom.ReactServerBatchingStrategy.batchedUpdates)
- description and source-code
```javascript
batchedUpdates = function (callback) {
  // Don't do anything here. During the server rendering we don't want to
  // schedule any updates. We will simply ignore them.
}
```
- example usage
```shell
...
  //
  // Batching is necessary here in order to ensure that all event handlers run
  // before the next rerender (including event handlers attached to ancestor
  // elements instead of directly on the input). Without this, controlled
  // components don't work properly in conjunction with event bubbling because
  // the component is rerendered and the value reverted before all the event
  // handlers can run. See https://github.com/facebook/react/issues/708.
  ReactUpdates.batchedUpdates(runEventInBatch, event);
}

function runEventInBatch(event) {
  EventPluginHub.enqueueEvents(event);
  EventPluginHub.processEventQueue(false);
}
...
```



# <a name="apidoc.module.react-dom.ReactServerRendering"></a>[module react-dom.ReactServerRendering](#apidoc.module.react-dom.ReactServerRendering)

#### <a name="apidoc.element.react-dom.ReactServerRendering.renderToStaticMarkup"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerRendering.</span>renderToStaticMarkup (element)](#apidoc.element.react-dom.ReactServerRendering.renderToStaticMarkup)
- description and source-code
```javascript
function renderToStaticMarkup(element) {
  !React.isValidElement(element) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'renderToStaticMarkup(): You must pass
 a valid ReactElement.') : _prodInvariant('47') : void 0;
  return renderToStringImpl(element, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactServerRendering.renderToString"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerRendering.</span>renderToString (element)](#apidoc.element.react-dom.ReactServerRendering.renderToString)
- description and source-code
```javascript
function renderToString(element) {
  !React.isValidElement(element) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'renderToString(): You must pass a valid
 ReactElement.') : _prodInvariant('46') : void 0;
  return renderToStringImpl(element, false);
}
```
- example usage
```shell
...

class MyComponent extends React.Component {
  render() {
    return <div>Hello World</div>;
  }
}

ReactDOMServer.renderToString(<MyComponent />);
'''

## API

### 'react-dom'

- 'findDOMNode'
...
```



# <a name="apidoc.module.react-dom.ReactServerRenderingTransaction"></a>[module react-dom.ReactServerRenderingTransaction](#apidoc.module.react-dom.ReactServerRenderingTransaction)

#### <a name="apidoc.element.react-dom.ReactServerRenderingTransaction.ReactServerRenderingTransaction"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ReactServerRenderingTransaction (renderToStaticMarkup)](#apidoc.element.react-dom.ReactServerRenderingTransaction.ReactServerRenderingTransaction)
- description and source-code
```javascript
function ReactServerRenderingTransaction(renderToStaticMarkup) {
  this.reinitializeTransaction();
  this.renderToStaticMarkup = renderToStaticMarkup;
  this.useCreateElement = false;
  this.updateQueue = new ReactServerUpdateQueue(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactServerRenderingTransaction.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.</span>getPooled (copyFieldsFrom)](#apidoc.element.react-dom.ReactServerRenderingTransaction.getPooled)
- description and source-code
```javascript
getPooled = function (copyFieldsFrom) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, copyFieldsFrom);
    return instance;
  } else {
    return new Klass(copyFieldsFrom);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.ReactServerRenderingTransaction.release"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.</span>release (instance)](#apidoc.element.react-dom.ReactServerRenderingTransaction.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.ReactServerRenderingTransaction.prototype"></a>[module react-dom.ReactServerRenderingTransaction.prototype](#apidoc.module.react-dom.ReactServerRenderingTransaction.prototype)

#### <a name="apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.checkpoint"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>checkpoint ()](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.checkpoint)
- description and source-code
```javascript
checkpoint = function () {}
```
- example usage
```shell
...
  } else {
    return Component(publicProps, publicContext, updateQueue);
  }
},

performInitialMountWithErrorHandling: function (renderedElement, hostParent, hostContainerInfo, transaction, context) {
  var markup;
  var checkpoint = transaction.checkpoint();
  try {
    markup = this.performInitialMount(renderedElement, hostParent, hostContainerInfo, transaction, context);
  } catch (e) {
    // Roll back to checkpoint, handle error (which may add items to the transaction), and take a new checkpoint
    transaction.rollback(checkpoint);
    this._instance.unstable_handleError(e);
    if (this._pendingStateQueue) {
...
```

#### <a name="apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.closeAll"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>closeAll (startIndex)](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.closeAll)
- description and source-code
```javascript
closeAll = function (startIndex) {
  !this.isInTransaction() ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Transaction.closeAll(): Cannot close transaction
 when none are open.') : _prodInvariant('28') : void 0;
  var transactionWrappers = this.transactionWrappers;
  for (var i = startIndex; i < transactionWrappers.length; i++) {
    var wrapper = transactionWrappers[i];
    var initData = this.wrapperInitData[i];
    var errorThrown;
    try {
      // Catching errors makes debugging more difficult, so we start with
      // errorThrown set to true before setting it to false after calling
      // close -- if it's still set to true in the finally block, it means
      // wrapper.close threw.
      errorThrown = true;
      if (initData !== OBSERVED_ERROR && wrapper.close) {
        wrapper.close.call(this, initData);
      }
      errorThrown = false;
    } finally {
      if (errorThrown) {
        // The closer for wrapper i threw an error; close the remaining
        // wrappers but silence any exceptions from them to ensure that the
        // first error is the one to bubble up.
        try {
          this.closeAll(i + 1);
        } catch (e) {}
      }
    }
  }
  this.wrapperInitData.length = 0;
}
```
- example usage
```shell
...
  errorThrown = false;
} finally {
  try {
    if (errorThrown) {
      // If 'method' throws, prefer to show that stack trace over any thrown
      // by invoking 'closeAll'.
      try {
        this.closeAll(0);
      } catch (err) {}
    } else {
      // Since 'method' didn't throw, we don't want to silence the exception
      // here.
      this.closeAll(0);
    }
  } finally {
...
```

#### <a name="apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.destructor"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>destructor ()](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.destructor)
- description and source-code
```javascript
destructor = function () {}
```
- example usage
```shell
...
    return new Klass(a1, a2, a3, a4);
  }
};

var standardReleaser = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
};

var DEFAULT_POOL_SIZE = 10;
var DEFAULT_POOLER = oneArgumentPooler;
...
```

#### <a name="apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.getReactMountReady"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>getReactMountReady ()](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.getReactMountReady)
- description and source-code
```javascript
getReactMountReady = function () {
  return noopCallbackQueue;
}
```
- example usage
```shell
...
  markup = this.performInitialMountWithErrorHandling(renderedElement, hostParent, hostContainerInfo, transaction, context);
} else {
  markup = this.performInitialMount(renderedElement, hostParent, hostContainerInfo, transaction, context);
}

if (inst.componentDidMount) {
  if (process.env.NODE_ENV !== 'production') {
    transaction.getReactMountReady().enqueue(function () {
      measureLifeCyclePerf(function () {
        return inst.componentDidMount();
      }, _this._debugID, 'componentDidMount');
    });
  } else {
    transaction.getReactMountReady().enqueue(inst.componentDidMount, inst);
  }
...
```

#### <a name="apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.getTransactionWrappers"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>getTransactionWrappers ()](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.getTransactionWrappers)
- description and source-code
```javascript
getTransactionWrappers = function () {
  return TRANSACTION_WRAPPERS;
}
```
- example usage
```shell
...
 * Sets up this instance so that it is prepared for collecting metrics. Does
 * so such that this setup method may be used on an instance that is already
 * initialized, in a way that does not consume additional memory upon reuse.
 * That can be useful if you decide to make your subclass of this mixin a
 * "PooledClass".
 */
reinitializeTransaction: function () {
  this.transactionWrappers = this.getTransactionWrappers();
  if (this.wrapperInitData) {
    this.wrapperInitData.length = 0;
  } else {
    this.wrapperInitData = [];
  }
  this._isInTransaction = false;
},
...
```

#### <a name="apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.getUpdateQueue"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>getUpdateQueue ()](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.getUpdateQueue)
- description and source-code
```javascript
getUpdateQueue = function () {
  return this.updateQueue;
}
```
- example usage
```shell
...
this._hostContainerInfo = hostContainerInfo;

var publicProps = this._currentElement.props;
var publicContext = this._processContext(context);

var Component = this._currentElement.type;

var updateQueue = transaction.getUpdateQueue();

// Initialize the public class
var doConstruct = shouldConstruct(Component);
var inst = this._constructComponent(doConstruct, publicProps, publicContext, updateQueue);
var renderedElement;

// Support functional components
...
```

#### <a name="apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.initializeAll"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>initializeAll (startIndex)](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.initializeAll)
- description and source-code
```javascript
initializeAll = function (startIndex) {
  var transactionWrappers = this.transactionWrappers;
  for (var i = startIndex; i < transactionWrappers.length; i++) {
    var wrapper = transactionWrappers[i];
    try {
      // Catching errors makes debugging more difficult, so we start with the
      // OBSERVED_ERROR state before overwriting it with the real return value
      // of initialize -- if it's still set to OBSERVED_ERROR in the finally
      // block, it means wrapper.initialize threw.
      this.wrapperInitData[i] = OBSERVED_ERROR;
      this.wrapperInitData[i] = wrapper.initialize ? wrapper.initialize.call(this) : null;
    } finally {
      if (this.wrapperInitData[i] === OBSERVED_ERROR) {
        // The initializer for wrapper i threw an error; initialize the
        // remaining wrappers but silence any exceptions from them to ensure
        // that the first error is the one to bubble up.
        try {
          this.initializeAll(i + 1);
        } catch (err) {}
      }
    }
  }
}
```
- example usage
```shell
...
try {
  this._isInTransaction = true;
  // Catching errors makes debugging more difficult, so we start with
  // errorThrown set to true before setting it to false after calling
  // close -- if it's still set to true in the finally block, it means
  // one of these calls threw.
  errorThrown = true;
  this.initializeAll(0);
  ret = method.call(scope, a, b, c, d, e, f);
  errorThrown = false;
} finally {
  try {
    if (errorThrown) {
      // If 'method' throws, prefer to show that stack trace over any thrown
      // by invoking 'closeAll'.
...
```

#### <a name="apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.isInTransaction"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>isInTransaction ()](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.isInTransaction)
- description and source-code
```javascript
isInTransaction = function () {
  return !!this._isInTransaction;
}
```
- example usage
```shell
...
 * @param {ReactClass} publicInstance The instance to use as 'this' context.
 * @param {?function} callback Called after state is updated.
 * @internal
 */


ReactServerUpdateQueue.prototype.enqueueCallback = function enqueueCallback(publicInstance, callback, callerName) {
  if (this.transaction.isInTransaction()) {
    ReactUpdateQueue.enqueueCallback(publicInstance, callback, callerName);
  }
};

/**
 * Forces an update. This should only be invoked when it is known with
 * certainty that we are **not** in a DOM transaction.
...
```

#### <a name="apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.perform"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>perform (method, scope, a, b, c, d, e, f)](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.perform)
- description and source-code
```javascript
perform = function (method, scope, a, b, c, d, e, f) {
  !!this.isInTransaction() ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Transaction.perform(...): Cannot initialize
 a transaction when there is already an outstanding transaction.') : _prodInvariant('27') : void 0;
  var errorThrown;
  var ret;
  try {
    this._isInTransaction = true;
    // Catching errors makes debugging more difficult, so we start with
    // errorThrown set to true before setting it to false after calling
    // close -- if it's still set to true in the finally block, it means
    // one of these calls threw.
    errorThrown = true;
    this.initializeAll(0);
    ret = method.call(scope, a, b, c, d, e, f);
    errorThrown = false;
  } finally {
    try {
      if (errorThrown) {
        // If 'method' throws, prefer to show that stack trace over any thrown
        // by invoking 'closeAll'.
        try {
          this.closeAll(0);
        } catch (err) {}
      } else {
        // Since 'method' didn't throw, we don't want to silence the exception
        // here.
        this.closeAll(0);
      }
    } finally {
      this._isInTransaction = false;
    }
  }
  return ret;
}
```
- example usage
```shell
...

    ReactDefaultBatchingStrategy.isBatchingUpdates = true;

    // The code is written this way to avoid extra allocations
    if (alreadyBatchingUpdates) {
      return callback(a, b, c, d, e);
    } else {
      return transaction.perform(callback, null, a, b, c, d, e);
    }
  }
};

module.exports = ReactDefaultBatchingStrategy;
...
```

#### <a name="apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.reinitializeTransaction"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>reinitializeTransaction ()](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.reinitializeTransaction)
- description and source-code
```javascript
reinitializeTransaction = function () {
  this.transactionWrappers = this.getTransactionWrappers();
  if (this.wrapperInitData) {
    this.wrapperInitData.length = 0;
  } else {
    this.wrapperInitData = [];
  }
  this._isInTransaction = false;
}
```
- example usage
```shell
...
  initialize: emptyFunction,
  close: ReactUpdates.flushBatchedUpdates.bind(ReactUpdates)
};

var TRANSACTION_WRAPPERS = [FLUSH_BATCHED_UPDATES, RESET_BATCHED_UPDATES];

function ReactDefaultBatchingStrategyTransaction() {
  this.reinitializeTransaction();
}

_assign(ReactDefaultBatchingStrategyTransaction.prototype, Transaction, {
  getTransactionWrappers: function () {
    return TRANSACTION_WRAPPERS;
  }
});
...
```

#### <a name="apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.rollback"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerRenderingTransaction.prototype.</span>rollback ()](#apidoc.element.react-dom.ReactServerRenderingTransaction.prototype.rollback)
- description and source-code
```javascript
rollback = function () {}
```
- example usage
```shell
...
  performInitialMountWithErrorHandling: function (renderedElement, hostParent, hostContainerInfo, transaction, context) {
    var markup;
    var checkpoint = transaction.checkpoint();
    try {
markup = this.performInitialMount(renderedElement, hostParent, hostContainerInfo, transaction, context);
    } catch (e) {
// Roll back to checkpoint, handle error (which may add items to the transaction), and take a new checkpoint
transaction.rollback(checkpoint);
this._instance.unstable_handleError(e);
if (this._pendingStateQueue) {
  this._instance.state = this._processPendingState(this._instance.props, this._instance.context);
}
checkpoint = transaction.checkpoint();

this._renderedComponent.unmountComponent(true);
...
```



# <a name="apidoc.module.react-dom.ReactServerUpdateQueue"></a>[module react-dom.ReactServerUpdateQueue](#apidoc.module.react-dom.ReactServerUpdateQueue)

#### <a name="apidoc.element.react-dom.ReactServerUpdateQueue.ReactServerUpdateQueue"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ReactServerUpdateQueue (transaction)](#apidoc.element.react-dom.ReactServerUpdateQueue.ReactServerUpdateQueue)
- description and source-code
```javascript
function ReactServerUpdateQueue(transaction) {
  _classCallCheck(this, ReactServerUpdateQueue);

  this.transaction = transaction;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactServerUpdateQueue.prototype"></a>[module react-dom.ReactServerUpdateQueue.prototype](#apidoc.module.react-dom.ReactServerUpdateQueue.prototype)

#### <a name="apidoc.element.react-dom.ReactServerUpdateQueue.prototype.enqueueCallback"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerUpdateQueue.prototype.</span>enqueueCallback (publicInstance, callback, callerName)](#apidoc.element.react-dom.ReactServerUpdateQueue.prototype.enqueueCallback)
- description and source-code
```javascript
function enqueueCallback(publicInstance, callback, callerName) {
  if (this.transaction.isInTransaction()) {
    ReactUpdateQueue.enqueueCallback(publicInstance, callback, callerName);
  }
}
```
- example usage
```shell
...
 * @param {?function} callback Called after state is updated.
 * @internal
 */


ReactServerUpdateQueue.prototype.enqueueCallback = function enqueueCallback(publicInstance, callback, callerName) {
  if (this.transaction.isInTransaction()) {
    ReactUpdateQueue.enqueueCallback(publicInstance, callback, callerName);
  }
};

/**
 * Forces an update. This should only be invoked when it is known with
 * certainty that we are **not** in a DOM transaction.
 *
...
```

#### <a name="apidoc.element.react-dom.ReactServerUpdateQueue.prototype.enqueueForceUpdate"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerUpdateQueue.prototype.</span>enqueueForceUpdate (publicInstance)](#apidoc.element.react-dom.ReactServerUpdateQueue.prototype.enqueueForceUpdate)
- description and source-code
```javascript
function enqueueForceUpdate(publicInstance) {
  if (this.transaction.isInTransaction()) {
    ReactUpdateQueue.enqueueForceUpdate(publicInstance);
  } else {
    warnNoop(publicInstance, 'forceUpdate');
  }
}
```
- example usage
```shell
...
 * @param {ReactClass} publicInstance The instance that should rerender.
 * @internal
 */


ReactServerUpdateQueue.prototype.enqueueForceUpdate = function enqueueForceUpdate(publicInstance) {
  if (this.transaction.isInTransaction()) {
    ReactUpdateQueue.enqueueForceUpdate(publicInstance);
  } else {
    warnNoop(publicInstance, 'forceUpdate');
  }
};

/**
 * Replaces all of the state. Always use this or 'setState' to mutate state.
...
```

#### <a name="apidoc.element.react-dom.ReactServerUpdateQueue.prototype.enqueueReplaceState"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerUpdateQueue.prototype.</span>enqueueReplaceState (publicInstance, completeState)](#apidoc.element.react-dom.ReactServerUpdateQueue.prototype.enqueueReplaceState)
- description and source-code
```javascript
function enqueueReplaceState(publicInstance, completeState) {
  if (this.transaction.isInTransaction()) {
    ReactUpdateQueue.enqueueReplaceState(publicInstance, completeState);
  } else {
    warnNoop(publicInstance, 'replaceState');
  }
}
```
- example usage
```shell
...
 * @param {object|function} completeState Next state.
 * @internal
 */


ReactServerUpdateQueue.prototype.enqueueReplaceState = function enqueueReplaceState(publicInstance, completeState) {
  if (this.transaction.isInTransaction()) {
    ReactUpdateQueue.enqueueReplaceState(publicInstance, completeState);
  } else {
    warnNoop(publicInstance, 'replaceState');
  }
};

/**
 * Sets a subset of the state. This only exists because _pendingState is
...
```

#### <a name="apidoc.element.react-dom.ReactServerUpdateQueue.prototype.enqueueSetState"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerUpdateQueue.prototype.</span>enqueueSetState (publicInstance, partialState)](#apidoc.element.react-dom.ReactServerUpdateQueue.prototype.enqueueSetState)
- description and source-code
```javascript
function enqueueSetState(publicInstance, partialState) {
  if (this.transaction.isInTransaction()) {
    ReactUpdateQueue.enqueueSetState(publicInstance, partialState);
  } else {
    warnNoop(publicInstance, 'setState');
  }
}
```
- example usage
```shell
...
   * @param {object|function} partialState Next partial state to be merged with state.
   * @internal
   */


  ReactServerUpdateQueue.prototype.enqueueSetState = function enqueueSetState(publicInstance, partialState) {
    if (this.transaction.isInTransaction()) {
      ReactUpdateQueue.enqueueSetState(publicInstance, partialState);
    } else {
      warnNoop(publicInstance, 'setState');
    }
  };

  return ReactServerUpdateQueue;
}();
...
```

#### <a name="apidoc.element.react-dom.ReactServerUpdateQueue.prototype.isMounted"></a>[function <span class="apidocSignatureSpan">react-dom.ReactServerUpdateQueue.prototype.</span>isMounted (publicInstance)](#apidoc.element.react-dom.ReactServerUpdateQueue.prototype.isMounted)
- description and source-code
```javascript
function isMounted(publicInstance) {
  return false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactShallowRenderer"></a>[module react-dom.ReactShallowRenderer](#apidoc.module.react-dom.ReactShallowRenderer)

#### <a name="apidoc.element.react-dom.ReactShallowRenderer.ReactShallowRenderer"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ReactShallowRenderer ()](#apidoc.element.react-dom.ReactShallowRenderer.ReactShallowRenderer)
- description and source-code
```javascript
function ReactShallowRenderer() {
  _classCallCheck(this, ReactShallowRenderer);

  this._instance = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactShallowRenderer.createRenderer"></a>[function <span class="apidocSignatureSpan">react-dom.ReactShallowRenderer.</span>createRenderer ()](#apidoc.element.react-dom.ReactShallowRenderer.createRenderer)
- description and source-code
```javascript
createRenderer = function () {
  return new ReactShallowRenderer();
}
```
- example usage
```shell
...
var invariant = require('fbjs/lib/invariant');
var warning = require('fbjs/lib/warning');

var topLevelTypes = EventConstants.topLevelTypes;

function Event(suffix) {}

// In react 16+ shallowRenderer will not be accessible via ReactTestUtils.createRenderer()
// Instead it will be available via react-test-renderer/shallow
// Maintain backwards compat for 15.5.0 release, but warn about using the deprecated method
var hasWarnedAboutCreateRenderer = false;
function createRendererWithWarning() {
process.env.NODE_ENV !== 'production' ? warning(hasWarnedAboutCreateRenderer, 'Shallow renderer has been moved to react-test-renderer
/shallow. ' + 'Update references to remove this warning.') : void 0;
hasWarnedAboutCreateRenderer = true;
...
```



# <a name="apidoc.module.react-dom.ReactShallowRenderer.prototype"></a>[module react-dom.ReactShallowRenderer.prototype](#apidoc.module.react-dom.ReactShallowRenderer.prototype)

#### <a name="apidoc.element.react-dom.ReactShallowRenderer.prototype._render"></a>[function <span class="apidocSignatureSpan">react-dom.ReactShallowRenderer.prototype.</span>_render (element, transaction, context)](#apidoc.element.react-dom.ReactShallowRenderer.prototype._render)
- description and source-code
```javascript
function _render(element, transaction, context) {
  if (this._instance) {
    ReactReconciler.receiveComponent(this._instance, element, transaction, context);
  } else {
    var instance = new ShallowComponentWrapper(element);
    ReactReconciler.mountComponent(instance, transaction, null, null, context, 0);
    this._instance = instance;
  }
}
```
- example usage
```shell
...
},
_replaceNodeWithMarkup: function () {},
_renderValidatedComponent: ReactCompositeComponent._renderValidatedComponentWithoutOwnerOrContext
});

function _batchedRender(renderer, element, context) {
var transaction = ReactUpdates.ReactReconcileTransaction.getPooled(true);
renderer._render(element, transaction, context);
ReactUpdates.ReactReconcileTransaction.release(transaction);
}

var ReactShallowRenderer = function () {
function ReactShallowRenderer() {
  _classCallCheck(this, ReactShallowRenderer);
...
```

#### <a name="apidoc.element.react-dom.ReactShallowRenderer.prototype.getMountedInstance"></a>[function <span class="apidocSignatureSpan">react-dom.ReactShallowRenderer.prototype.</span>getMountedInstance ()](#apidoc.element.react-dom.ReactShallowRenderer.prototype.getMountedInstance)
- description and source-code
```javascript
function getMountedInstance() {
  return this._instance ? this._instance._instance : null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactShallowRenderer.prototype.getRenderOutput"></a>[function <span class="apidocSignatureSpan">react-dom.ReactShallowRenderer.prototype.</span>getRenderOutput ()](#apidoc.element.react-dom.ReactShallowRenderer.prototype.getRenderOutput)
- description and source-code
```javascript
function getRenderOutput() {
  return this._instance && this._instance._renderedComponent && this._instance._renderedComponent._renderedOutput || null;
}
```
- example usage
```shell
...
  !(typeof element.type !== 'string') ? process.env.NODE_ENV !== 'production' ? invariant(false, 'ReactShallowRenderer render():
Shallow rendering works only with custom components, not primitives (%s). Instead of calling '.render(el)' and inspecting the rendered
 output, look at 'el.props' directly instead.', element.type) : _prodInvariant('13', element.type) : void 0;

  if (!context) {
    context = emptyObject;
  }
  ReactUpdates.batchedUpdates(_batchedRender, this, element, context);

  return this.getRenderOutput();
};

ReactShallowRenderer.prototype.getRenderOutput = function getRenderOutput() {
  return this._instance && this._instance._renderedComponent && this._instance._renderedComponent._renderedOutput || null;
};

ReactShallowRenderer.prototype.unmount = function unmount() {
...
```

#### <a name="apidoc.element.react-dom.ReactShallowRenderer.prototype.render"></a>[function <span class="apidocSignatureSpan">react-dom.ReactShallowRenderer.prototype.</span>render (element, context)](#apidoc.element.react-dom.ReactShallowRenderer.prototype.render)
- description and source-code
```javascript
function render(element, context) {
  // Ensure we've done the default injections. This might not be true in the
  // case of a simple test that only requires React and the TestUtils in
  // conjunction with an inline-requires transform.
  injectDefaults();

  !React.isValidElement(element) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'ReactShallowRenderer render(): Invalid
 component element.%s', typeof element === 'function' ? ' Instead of passing a component class, make sure to instantiate ' + 'it
 by passing it to React.createElement.' : '') : _prodInvariant('12', typeof element === 'function' ? ' Instead of passing a component
 class, make sure to instantiate ' + 'it by passing it to React.createElement.' : '') : void 0;
  !(typeof element.type !== 'string') ? process.env.NODE_ENV !== 'production' ? invariant(false, 'ReactShallowRenderer render():
Shallow rendering works only with custom components, not primitives (%s). Instead of calling '.render(el)' and inspecting the rendered
 output, look at 'el.props' directly instead.', element.type) : _prodInvariant('13', element.type) : void 0;

  if (!context) {
    context = emptyObject;
  }
  ReactUpdates.batchedUpdates(_batchedRender, this, element, context);

  return this.getRenderOutput();
}
```
- example usage
```shell
...

class MyComponent extends React.Component {
  render() {
    return <div>Hello World</div>;
  }
}

ReactDOM.render(<MyComponent />, node);
'''

### On the server

'''js
var React = require('react');
var ReactDOMServer = require('react-dom/server');
...
```

#### <a name="apidoc.element.react-dom.ReactShallowRenderer.prototype.unmount"></a>[function <span class="apidocSignatureSpan">react-dom.ReactShallowRenderer.prototype.</span>unmount ()](#apidoc.element.react-dom.ReactShallowRenderer.prototype.unmount)
- description and source-code
```javascript
function unmount() {
  if (this._instance) {
    ReactReconciler.unmountComponent(this._instance, false);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactSimpleEmptyComponent"></a>[module react-dom.ReactSimpleEmptyComponent](#apidoc.module.react-dom.ReactSimpleEmptyComponent)

#### <a name="apidoc.element.react-dom.ReactSimpleEmptyComponent.ReactSimpleEmptyComponent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ReactSimpleEmptyComponent (placeholderElement, instantiate)](#apidoc.element.react-dom.ReactSimpleEmptyComponent.ReactSimpleEmptyComponent)
- description and source-code
```javascript
ReactSimpleEmptyComponent = function (placeholderElement, instantiate) {
  this._currentElement = null;
  this._renderedComponent = instantiate(placeholderElement);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ReactSimpleEmptyComponent.prototype"></a>[module react-dom.ReactSimpleEmptyComponent.prototype](#apidoc.module.react-dom.ReactSimpleEmptyComponent.prototype)

#### <a name="apidoc.element.react-dom.ReactSimpleEmptyComponent.prototype.getHostNode"></a>[function <span class="apidocSignatureSpan">react-dom.ReactSimpleEmptyComponent.prototype.</span>getHostNode ()](#apidoc.element.react-dom.ReactSimpleEmptyComponent.prototype.getHostNode)
- description and source-code
```javascript
getHostNode = function () {
  return ReactReconciler.getHostNode(this._renderedComponent);
}
```
- example usage
```shell
...
var prevElement = prevChild && prevChild._currentElement;
var nextElement = nextChildren[name];
if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
  ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
  nextChildren[name] = prevChild;
} else {
  if (prevChild) {
    removedNodes[name] = ReactReconciler.getHostNode(prevChild);
    ReactReconciler.unmountComponent(prevChild, false);
  }
  // The child must be instantiated before it's mounted.
  var nextChildInstance = instantiateReactComponent(nextElement, true);
  nextChildren[name] = nextChildInstance;
  // Creating mount image now ensures refs are resolved in right order
  // (see https://github.com/facebook/react/pull/7101 for explanation).
...
```

#### <a name="apidoc.element.react-dom.ReactSimpleEmptyComponent.prototype.mountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactSimpleEmptyComponent.prototype.</span>mountComponent (transaction, hostParent, hostContainerInfo, context, parentDebugID // 0 in production and for roots )](#apidoc.element.react-dom.ReactSimpleEmptyComponent.prototype.mountComponent)
- description and source-code
```javascript
mountComponent = function (transaction, hostParent, hostContainerInfo, context, parentDebugID // 0 in production and for roots ) {
  return ReactReconciler.mountComponent(this._renderedComponent, transaction, hostParent, hostContainerInfo, context, parentDebugID
);
}
```
- example usage
```shell
...
      ReactReconciler.unmountComponent(prevChild, false);
    }
    // The child must be instantiated before it's mounted.
    var nextChildInstance = instantiateReactComponent(nextElement, true);
    nextChildren[name] = nextChildInstance;
    // Creating mount image now ensures refs are resolved in right order
    // (see https://github.com/facebook/react/pull/7101 for explanation).
    var nextChildMountImage = ReactReconciler.mountComponent(nextChildInstance, transaction, hostParent, hostContainerInfo, context
, selfDebugID);
    mountImages.push(nextChildMountImage);
  }
}
// Unmount children that are no longer present.
for (name in prevChildren) {
  if (prevChildren.hasOwnProperty(name) && !(nextChildren && nextChildren.hasOwnProperty(name))) {
    prevChild = prevChildren[name];
...
```

#### <a name="apidoc.element.react-dom.ReactSimpleEmptyComponent.prototype.receiveComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactSimpleEmptyComponent.prototype.</span>receiveComponent ()](#apidoc.element.react-dom.ReactSimpleEmptyComponent.prototype.receiveComponent)
- description and source-code
```javascript
receiveComponent = function () {}
```
- example usage
```shell
...
if (!nextChildren.hasOwnProperty(name)) {
  continue;
}
prevChild = prevChildren && prevChildren[name];
var prevElement = prevChild && prevChild._currentElement;
var nextElement = nextChildren[name];
if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
  ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
  nextChildren[name] = prevChild;
} else {
  if (prevChild) {
    removedNodes[name] = ReactReconciler.getHostNode(prevChild);
    ReactReconciler.unmountComponent(prevChild, false);
  }
  // The child must be instantiated before it's mounted.
...
```

#### <a name="apidoc.element.react-dom.ReactSimpleEmptyComponent.prototype.unmountComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactSimpleEmptyComponent.prototype.</span>unmountComponent ()](#apidoc.element.react-dom.ReactSimpleEmptyComponent.prototype.unmountComponent)
- description and source-code
```javascript
unmountComponent = function () {
  ReactReconciler.unmountComponent(this._renderedComponent);
  this._renderedComponent = null;
}
```
- example usage
```shell
...
var nextElement = nextChildren[name];
if (prevChild != null && shouldUpdateReactComponent(prevElement, nextElement)) {
  ReactReconciler.receiveComponent(prevChild, nextElement, transaction, context);
  nextChildren[name] = prevChild;
} else {
  if (prevChild) {
    removedNodes[name] = ReactReconciler.getHostNode(prevChild);
    ReactReconciler.unmountComponent(prevChild, false);
  }
  // The child must be instantiated before it's mounted.
  var nextChildInstance = instantiateReactComponent(nextElement, true);
  nextChildren[name] = nextChildInstance;
  // Creating mount image now ensures refs are resolved in right order
  // (see https://github.com/facebook/react/pull/7101 for explanation).
  var nextChildMountImage = ReactReconciler.mountComponent(nextChildInstance, transaction, hostParent, hostContainerInfo, context
, selfDebugID);
...
```



# <a name="apidoc.module.react-dom.ReactTestReconcileTransaction"></a>[module react-dom.ReactTestReconcileTransaction](#apidoc.module.react-dom.ReactTestReconcileTransaction)

#### <a name="apidoc.element.react-dom.ReactTestReconcileTransaction.ReactTestReconcileTransaction"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ReactTestReconcileTransaction (testOptions)](#apidoc.element.react-dom.ReactTestReconcileTransaction.ReactTestReconcileTransaction)
- description and source-code
```javascript
function ReactTestReconcileTransaction(testOptions) {
  this.reinitializeTransaction();
  this.testOptions = testOptions;
  this.reactMountReady = CallbackQueue.getPooled(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactTestReconcileTransaction.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.</span>getPooled (copyFieldsFrom)](#apidoc.element.react-dom.ReactTestReconcileTransaction.getPooled)
- description and source-code
```javascript
getPooled = function (copyFieldsFrom) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, copyFieldsFrom);
    return instance;
  } else {
    return new Klass(copyFieldsFrom);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.ReactTestReconcileTransaction.release"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.</span>release (instance)](#apidoc.element.react-dom.ReactTestReconcileTransaction.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.ReactTestReconcileTransaction.prototype"></a>[module react-dom.ReactTestReconcileTransaction.prototype](#apidoc.module.react-dom.ReactTestReconcileTransaction.prototype)

#### <a name="apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.checkpoint"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>checkpoint ()](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.checkpoint)
- description and source-code
```javascript
checkpoint = function () {
  // reactMountReady is the our only stateful wrapper
  return this.reactMountReady.checkpoint();
}
```
- example usage
```shell
...
  } else {
    return Component(publicProps, publicContext, updateQueue);
  }
},

performInitialMountWithErrorHandling: function (renderedElement, hostParent, hostContainerInfo, transaction, context) {
  var markup;
  var checkpoint = transaction.checkpoint();
  try {
    markup = this.performInitialMount(renderedElement, hostParent, hostContainerInfo, transaction, context);
  } catch (e) {
    // Roll back to checkpoint, handle error (which may add items to the transaction), and take a new checkpoint
    transaction.rollback(checkpoint);
    this._instance.unstable_handleError(e);
    if (this._pendingStateQueue) {
...
```

#### <a name="apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.closeAll"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>closeAll (startIndex)](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.closeAll)
- description and source-code
```javascript
closeAll = function (startIndex) {
  !this.isInTransaction() ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Transaction.closeAll(): Cannot close transaction
 when none are open.') : _prodInvariant('28') : void 0;
  var transactionWrappers = this.transactionWrappers;
  for (var i = startIndex; i < transactionWrappers.length; i++) {
    var wrapper = transactionWrappers[i];
    var initData = this.wrapperInitData[i];
    var errorThrown;
    try {
      // Catching errors makes debugging more difficult, so we start with
      // errorThrown set to true before setting it to false after calling
      // close -- if it's still set to true in the finally block, it means
      // wrapper.close threw.
      errorThrown = true;
      if (initData !== OBSERVED_ERROR && wrapper.close) {
        wrapper.close.call(this, initData);
      }
      errorThrown = false;
    } finally {
      if (errorThrown) {
        // The closer for wrapper i threw an error; close the remaining
        // wrappers but silence any exceptions from them to ensure that the
        // first error is the one to bubble up.
        try {
          this.closeAll(i + 1);
        } catch (e) {}
      }
    }
  }
  this.wrapperInitData.length = 0;
}
```
- example usage
```shell
...
  errorThrown = false;
} finally {
  try {
    if (errorThrown) {
      // If 'method' throws, prefer to show that stack trace over any thrown
      // by invoking 'closeAll'.
      try {
        this.closeAll(0);
      } catch (err) {}
    } else {
      // Since 'method' didn't throw, we don't want to silence the exception
      // here.
      this.closeAll(0);
    }
  } finally {
...
```

#### <a name="apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.destructor"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>destructor ()](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.destructor)
- description and source-code
```javascript
destructor = function () {
  CallbackQueue.release(this.reactMountReady);
  this.reactMountReady = null;
}
```
- example usage
```shell
...
    return new Klass(a1, a2, a3, a4);
  }
};

var standardReleaser = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
};

var DEFAULT_POOL_SIZE = 10;
var DEFAULT_POOLER = oneArgumentPooler;
...
```

#### <a name="apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.getReactMountReady"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>getReactMountReady ()](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.getReactMountReady)
- description and source-code
```javascript
getReactMountReady = function () {
  return this.reactMountReady;
}
```
- example usage
```shell
...
  markup = this.performInitialMountWithErrorHandling(renderedElement, hostParent, hostContainerInfo, transaction, context);
} else {
  markup = this.performInitialMount(renderedElement, hostParent, hostContainerInfo, transaction, context);
}

if (inst.componentDidMount) {
  if (process.env.NODE_ENV !== 'production') {
    transaction.getReactMountReady().enqueue(function () {
      measureLifeCyclePerf(function () {
        return inst.componentDidMount();
      }, _this._debugID, 'componentDidMount');
    });
  } else {
    transaction.getReactMountReady().enqueue(inst.componentDidMount, inst);
  }
...
```

#### <a name="apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.getTestOptions"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>getTestOptions ()](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.getTestOptions)
- description and source-code
```javascript
getTestOptions = function () {
  return this.testOptions;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.getTransactionWrappers"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>getTransactionWrappers ()](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.getTransactionWrappers)
- description and source-code
```javascript
getTransactionWrappers = function () {
  return TRANSACTION_WRAPPERS;
}
```
- example usage
```shell
...
 * Sets up this instance so that it is prepared for collecting metrics. Does
 * so such that this setup method may be used on an instance that is already
 * initialized, in a way that does not consume additional memory upon reuse.
 * That can be useful if you decide to make your subclass of this mixin a
 * "PooledClass".
 */
reinitializeTransaction: function () {
  this.transactionWrappers = this.getTransactionWrappers();
  if (this.wrapperInitData) {
    this.wrapperInitData.length = 0;
  } else {
    this.wrapperInitData = [];
  }
  this._isInTransaction = false;
},
...
```

#### <a name="apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.getUpdateQueue"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>getUpdateQueue ()](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.getUpdateQueue)
- description and source-code
```javascript
getUpdateQueue = function () {
  return ReactUpdateQueue;
}
```
- example usage
```shell
...
this._hostContainerInfo = hostContainerInfo;

var publicProps = this._currentElement.props;
var publicContext = this._processContext(context);

var Component = this._currentElement.type;

var updateQueue = transaction.getUpdateQueue();

// Initialize the public class
var doConstruct = shouldConstruct(Component);
var inst = this._constructComponent(doConstruct, publicProps, publicContext, updateQueue);
var renderedElement;

// Support functional components
...
```

#### <a name="apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.initializeAll"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>initializeAll (startIndex)](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.initializeAll)
- description and source-code
```javascript
initializeAll = function (startIndex) {
  var transactionWrappers = this.transactionWrappers;
  for (var i = startIndex; i < transactionWrappers.length; i++) {
    var wrapper = transactionWrappers[i];
    try {
      // Catching errors makes debugging more difficult, so we start with the
      // OBSERVED_ERROR state before overwriting it with the real return value
      // of initialize -- if it's still set to OBSERVED_ERROR in the finally
      // block, it means wrapper.initialize threw.
      this.wrapperInitData[i] = OBSERVED_ERROR;
      this.wrapperInitData[i] = wrapper.initialize ? wrapper.initialize.call(this) : null;
    } finally {
      if (this.wrapperInitData[i] === OBSERVED_ERROR) {
        // The initializer for wrapper i threw an error; initialize the
        // remaining wrappers but silence any exceptions from them to ensure
        // that the first error is the one to bubble up.
        try {
          this.initializeAll(i + 1);
        } catch (err) {}
      }
    }
  }
}
```
- example usage
```shell
...
try {
  this._isInTransaction = true;
  // Catching errors makes debugging more difficult, so we start with
  // errorThrown set to true before setting it to false after calling
  // close -- if it's still set to true in the finally block, it means
  // one of these calls threw.
  errorThrown = true;
  this.initializeAll(0);
  ret = method.call(scope, a, b, c, d, e, f);
  errorThrown = false;
} finally {
  try {
    if (errorThrown) {
      // If 'method' throws, prefer to show that stack trace over any thrown
      // by invoking 'closeAll'.
...
```

#### <a name="apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.isInTransaction"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>isInTransaction ()](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.isInTransaction)
- description and source-code
```javascript
isInTransaction = function () {
  return !!this._isInTransaction;
}
```
- example usage
```shell
...
 * @param {ReactClass} publicInstance The instance to use as 'this' context.
 * @param {?function} callback Called after state is updated.
 * @internal
 */


ReactServerUpdateQueue.prototype.enqueueCallback = function enqueueCallback(publicInstance, callback, callerName) {
  if (this.transaction.isInTransaction()) {
    ReactUpdateQueue.enqueueCallback(publicInstance, callback, callerName);
  }
};

/**
 * Forces an update. This should only be invoked when it is known with
 * certainty that we are **not** in a DOM transaction.
...
```

#### <a name="apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.perform"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>perform (method, scope, a, b, c, d, e, f)](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.perform)
- description and source-code
```javascript
perform = function (method, scope, a, b, c, d, e, f) {
  !!this.isInTransaction() ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Transaction.perform(...): Cannot initialize
 a transaction when there is already an outstanding transaction.') : _prodInvariant('27') : void 0;
  var errorThrown;
  var ret;
  try {
    this._isInTransaction = true;
    // Catching errors makes debugging more difficult, so we start with
    // errorThrown set to true before setting it to false after calling
    // close -- if it's still set to true in the finally block, it means
    // one of these calls threw.
    errorThrown = true;
    this.initializeAll(0);
    ret = method.call(scope, a, b, c, d, e, f);
    errorThrown = false;
  } finally {
    try {
      if (errorThrown) {
        // If 'method' throws, prefer to show that stack trace over any thrown
        // by invoking 'closeAll'.
        try {
          this.closeAll(0);
        } catch (err) {}
      } else {
        // Since 'method' didn't throw, we don't want to silence the exception
        // here.
        this.closeAll(0);
      }
    } finally {
      this._isInTransaction = false;
    }
  }
  return ret;
}
```
- example usage
```shell
...

    ReactDefaultBatchingStrategy.isBatchingUpdates = true;

    // The code is written this way to avoid extra allocations
    if (alreadyBatchingUpdates) {
      return callback(a, b, c, d, e);
    } else {
      return transaction.perform(callback, null, a, b, c, d, e);
    }
  }
};

module.exports = ReactDefaultBatchingStrategy;
...
```

#### <a name="apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.reinitializeTransaction"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>reinitializeTransaction ()](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.reinitializeTransaction)
- description and source-code
```javascript
reinitializeTransaction = function () {
  this.transactionWrappers = this.getTransactionWrappers();
  if (this.wrapperInitData) {
    this.wrapperInitData.length = 0;
  } else {
    this.wrapperInitData = [];
  }
  this._isInTransaction = false;
}
```
- example usage
```shell
...
  initialize: emptyFunction,
  close: ReactUpdates.flushBatchedUpdates.bind(ReactUpdates)
};

var TRANSACTION_WRAPPERS = [FLUSH_BATCHED_UPDATES, RESET_BATCHED_UPDATES];

function ReactDefaultBatchingStrategyTransaction() {
  this.reinitializeTransaction();
}

_assign(ReactDefaultBatchingStrategyTransaction.prototype, Transaction, {
  getTransactionWrappers: function () {
    return TRANSACTION_WRAPPERS;
  }
});
...
```

#### <a name="apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.rollback"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestReconcileTransaction.prototype.</span>rollback (checkpoint)](#apidoc.element.react-dom.ReactTestReconcileTransaction.prototype.rollback)
- description and source-code
```javascript
rollback = function (checkpoint) {
  this.reactMountReady.rollback(checkpoint);
}
```
- example usage
```shell
...
  performInitialMountWithErrorHandling: function (renderedElement, hostParent, hostContainerInfo, transaction, context) {
    var markup;
    var checkpoint = transaction.checkpoint();
    try {
markup = this.performInitialMount(renderedElement, hostParent, hostContainerInfo, transaction, context);
    } catch (e) {
// Roll back to checkpoint, handle error (which may add items to the transaction), and take a new checkpoint
transaction.rollback(checkpoint);
this._instance.unstable_handleError(e);
if (this._pendingStateQueue) {
  this._instance.state = this._processPendingState(this._instance.props, this._instance.context);
}
checkpoint = transaction.checkpoint();

this._renderedComponent.unmountComponent(true);
...
```



# <a name="apidoc.module.react-dom.ReactTestUtils"></a>[module react-dom.ReactTestUtils](#apidoc.module.react-dom.ReactTestUtils)

#### <a name="apidoc.element.react-dom.ReactTestUtils.createRenderer"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>createRenderer ()](#apidoc.element.react-dom.ReactTestUtils.createRenderer)
- description and source-code
```javascript
function createRendererWithWarning() {
  process.env.NODE_ENV !== 'production' ? warning(hasWarnedAboutCreateRenderer, 'Shallow renderer has been moved to react-test-renderer
/shallow. ' + 'Update references to remove this warning.') : void 0;
  hasWarnedAboutCreateRenderer = true;

  return new ReactShallowRenderer();
}
```
- example usage
```shell
...
var invariant = require('fbjs/lib/invariant');
var warning = require('fbjs/lib/warning');

var topLevelTypes = EventConstants.topLevelTypes;

function Event(suffix) {}

// In react 16+ shallowRenderer will not be accessible via ReactTestUtils.createRenderer()
// Instead it will be available via react-test-renderer/shallow
// Maintain backwards compat for 15.5.0 release, but warn about using the deprecated method
var hasWarnedAboutCreateRenderer = false;
function createRendererWithWarning() {
process.env.NODE_ENV !== 'production' ? warning(hasWarnedAboutCreateRenderer, 'Shallow renderer has been moved to react-test-renderer
/shallow. ' + 'Update references to remove this warning.') : void 0;
hasWarnedAboutCreateRenderer = true;
...
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.findAllInRenderedTree"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>findAllInRenderedTree (inst, test)](#apidoc.element.react-dom.ReactTestUtils.findAllInRenderedTree)
- description and source-code
```javascript
findAllInRenderedTree = function (inst, test) {
  if (!inst) {
    return [];
  }
  !ReactTestUtils.isCompositeComponent(inst) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'findAllInRenderedTree(...):
instance must be a composite component') : _prodInvariant('10') : void 0;
  return findAllInRenderedTreeInternal(ReactInstanceMap.get(inst), test);
}
```
- example usage
```shell
...

/**
 * Finds all instance of components in the rendered tree that are DOM
 * components with the class name matching 'className'.
 * @return {array} an array of all the matches.
 */
scryRenderedDOMComponentsWithClass: function (root, classNames) {
  return ReactTestUtils.findAllInRenderedTree(root, function (inst) {
    if (ReactTestUtils.isDOMComponent(inst)) {
      var className = inst.className;
      if (typeof className !== 'string') {
        // SVG, probably.
        className = inst.getAttribute('class') || '';
      }
      var classList = className.split(/\s+/);
...
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.findRenderedComponentWithType"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>findRenderedComponentWithType (root, componentType)](#apidoc.element.react-dom.ReactTestUtils.findRenderedComponentWithType)
- description and source-code
```javascript
findRenderedComponentWithType = function (root, componentType) {
  var all = ReactTestUtils.scryRenderedComponentsWithType(root, componentType);
  if (all.length !== 1) {
    throw new Error('Did not find exactly one match (found: ' + all.length + ') ' + 'for componentType:' + componentType);
  }
  return all[0];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.findRenderedDOMComponentWithClass"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>findRenderedDOMComponentWithClass (root, className)](#apidoc.element.react-dom.ReactTestUtils.findRenderedDOMComponentWithClass)
- description and source-code
```javascript
findRenderedDOMComponentWithClass = function (root, className) {
  var all = ReactTestUtils.scryRenderedDOMComponentsWithClass(root, className);
  if (all.length !== 1) {
    throw new Error('Did not find exactly one match (found: ' + all.length + ') ' + 'for class:' + className);
  }
  return all[0];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.findRenderedDOMComponentWithTag"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>findRenderedDOMComponentWithTag (root, tagName)](#apidoc.element.react-dom.ReactTestUtils.findRenderedDOMComponentWithTag)
- description and source-code
```javascript
findRenderedDOMComponentWithTag = function (root, tagName) {
  var all = ReactTestUtils.scryRenderedDOMComponentsWithTag(root, tagName);
  if (all.length !== 1) {
    throw new Error('Did not find exactly one match (found: ' + all.length + ') ' + 'for tag:' + tagName);
  }
  return all[0];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.getRenderedChildOfCompositeComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>getRenderedChildOfCompositeComponent (inst)](#apidoc.element.react-dom.ReactTestUtils.getRenderedChildOfCompositeComponent)
- description and source-code
```javascript
getRenderedChildOfCompositeComponent = function (inst) {
  if (!ReactTestUtils.isCompositeComponent(inst)) {
    return null;
  }
  var internalInstance = ReactInstanceMap.get(inst);
  return internalInstance._renderedComponent.getPublicInstance();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.isCompositeComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>isCompositeComponent (inst)](#apidoc.element.react-dom.ReactTestUtils.isCompositeComponent)
- description and source-code
```javascript
isCompositeComponent = function (inst) {
  if (ReactTestUtils.isDOMComponent(inst)) {
    // Accessing inst.setState warns; just return false as that'll be what
    // this returns when we have DOM nodes as refs directly
    return false;
  }
  return inst != null && typeof inst.render === 'function' && typeof inst.setState === 'function';
}
```
- example usage
```shell
...
    // this returns when we have DOM nodes as refs directly
    return false;
  }
  return inst != null && typeof inst.render === 'function' && typeof inst.setState === 'function';
},

isCompositeComponentWithType: function (inst, type) {
  if (!ReactTestUtils.isCompositeComponent(inst)) {
    return false;
  }
  var internalInstance = ReactInstanceMap.get(inst);
  var constructor = internalInstance._currentElement.type;

  return constructor === type;
},
...
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.isCompositeComponentElement"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>isCompositeComponentElement (inst)](#apidoc.element.react-dom.ReactTestUtils.isCompositeComponentElement)
- description and source-code
```javascript
isCompositeComponentElement = function (inst) {
  if (!React.isValidElement(inst)) {
    return false;
  }
  // We check the prototype of the type that will get mounted, not the
  // instance itself. This is a future proof way of duck typing.
  var prototype = inst.type.prototype;
  return typeof prototype.render === 'function' && typeof prototype.setState === 'function';
}
```
- example usage
```shell
...
  return typeof prototype.render === 'function' && typeof prototype.setState === 'function';
},

isCompositeComponentElementWithType: function (inst, type) {
  var internalInstance = ReactInstanceMap.get(inst);
  var constructor = internalInstance._currentElement.type;

  return !!(ReactTestUtils.isCompositeComponentElement(inst) && constructor === type);
},

getRenderedChildOfCompositeComponent: function (inst) {
  if (!ReactTestUtils.isCompositeComponent(inst)) {
    return null;
  }
  var internalInstance = ReactInstanceMap.get(inst);
...
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.isCompositeComponentElementWithType"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>isCompositeComponentElementWithType (inst, type)](#apidoc.element.react-dom.ReactTestUtils.isCompositeComponentElementWithType)
- description and source-code
```javascript
isCompositeComponentElementWithType = function (inst, type) {
  var internalInstance = ReactInstanceMap.get(inst);
  var constructor = internalInstance._currentElement.type;

  return !!(ReactTestUtils.isCompositeComponentElement(inst) && constructor === type);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.isCompositeComponentWithType"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>isCompositeComponentWithType (inst, type)](#apidoc.element.react-dom.ReactTestUtils.isCompositeComponentWithType)
- description and source-code
```javascript
isCompositeComponentWithType = function (inst, type) {
  if (!ReactTestUtils.isCompositeComponent(inst)) {
    return false;
  }
  var internalInstance = ReactInstanceMap.get(inst);
  var constructor = internalInstance._currentElement.type;

  return constructor === type;
}
```
- example usage
```shell
...

/**
 * Finds all instances of components with type equal to 'componentType'.
 * @return {array} an array of all the matches.
 */
scryRenderedComponentsWithType: function (root, componentType) {
  return ReactTestUtils.findAllInRenderedTree(root, function (inst) {
    return ReactTestUtils.isCompositeComponentWithType(inst, componentType);
  });
},

/**
 * Same as 'scryRenderedComponentsWithType' but expects there to be one result
 * and returns that one result, or throws exception if there is any other
 * number of matches besides one.
...
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.isDOMComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>isDOMComponent (inst)](#apidoc.element.react-dom.ReactTestUtils.isDOMComponent)
- description and source-code
```javascript
isDOMComponent = function (inst) {
  return !!(inst && inst.nodeType === 1 && inst.tagName);
}
```
- example usage
```shell
...
function findAllInRenderedTreeInternal(inst, test) {
if (!inst || !inst.getPublicInstance) {
  return [];
}
var publicInst = inst.getPublicInstance();
var ret = test(publicInst) ? [publicInst] : [];
var currentElement = inst._currentElement;
if (ReactTestUtils.isDOMComponent(publicInst)) {
  var renderedChildren = inst._renderedChildren;
  var key;
  for (key in renderedChildren) {
    if (!renderedChildren.hasOwnProperty(key)) {
      continue;
    }
    ret = ret.concat(findAllInRenderedTreeInternal(renderedChildren[key], test));
...
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.isDOMComponentElement"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>isDOMComponentElement (inst)](#apidoc.element.react-dom.ReactTestUtils.isDOMComponentElement)
- description and source-code
```javascript
isDOMComponentElement = function (inst) {
  return !!(inst && React.isValidElement(inst) && !!inst.tagName);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.isElement"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>isElement (element)](#apidoc.element.react-dom.ReactTestUtils.isElement)
- description and source-code
```javascript
isElement = function (element) {
  return React.isValidElement(element);
}
```
- example usage
```shell
...
  expect(instance).not.toBeUndefined();

  !ReactTestUtils.isCompositeComponent(instance) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'reactComponentExpect
(...): instance must be a composite component') : _prodInvariant('15') : void 0;
  var internalInstance = ReactInstanceMap.get(instance);

  expect(typeof internalInstance).toBe('object');
  expect(typeof internalInstance.constructor).toBe('function');
  expect(ReactTestUtils.isElement(internalInstance)).toBe(false);

  return new reactComponentExpectInternal(internalInstance);
}

function reactComponentExpectInternal(internalInstance) {
  this._instance = internalInstance;
}
...
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.isElementOfType"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>isElementOfType (inst, convenienceConstructor)](#apidoc.element.react-dom.ReactTestUtils.isElementOfType)
- description and source-code
```javascript
isElementOfType = function (inst, convenienceConstructor) {
  return React.isValidElement(inst) && inst.type === convenienceConstructor;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.mockComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>mockComponent (module, mockTagName)](#apidoc.element.react-dom.ReactTestUtils.mockComponent)
- description and source-code
```javascript
mockComponent = function (module, mockTagName) {
  mockTagName = mockTagName || module.mockTagName || 'div';

  module.prototype.render.mockImplementation(function () {
    return React.createElement(mockTagName, null, this.props.children);
  });

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.nativeTouchData"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>nativeTouchData (x, y)](#apidoc.element.react-dom.ReactTestUtils.nativeTouchData)
- description and source-code
```javascript
nativeTouchData = function (x, y) {
  return {
    touches: [{ pageX: x, pageY: y }]
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.renderIntoDocument"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>renderIntoDocument (element)](#apidoc.element.react-dom.ReactTestUtils.renderIntoDocument)
- description and source-code
```javascript
renderIntoDocument = function (element) {
  var div = document.createElement('div');
  // None of our tests actually require attaching the container to the
  // DOM, and doing so creates a mess that we rely on test isolation to
  // clean up, so we're going to stop honoring the name of this method
  // (and probably rename it eventually) if no problems arise.
  // document.documentElement.appendChild(div);
  return ReactDOM.render(element, div);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.scryRenderedComponentsWithType"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>scryRenderedComponentsWithType (root, componentType)](#apidoc.element.react-dom.ReactTestUtils.scryRenderedComponentsWithType)
- description and source-code
```javascript
scryRenderedComponentsWithType = function (root, componentType) {
  return ReactTestUtils.findAllInRenderedTree(root, function (inst) {
    return ReactTestUtils.isCompositeComponentWithType(inst, componentType);
  });
}
```
- example usage
```shell
...
/**
 * Same as 'scryRenderedComponentsWithType' but expects there to be one result
 * and returns that one result, or throws exception if there is any other
 * number of matches besides one.
 * @return {!ReactComponent} The one match.
 */
findRenderedComponentWithType: function (root, componentType) {
  var all = ReactTestUtils.scryRenderedComponentsWithType(root, componentType);
  if (all.length !== 1) {
    throw new Error('Did not find exactly one match (found: ' + all.length + ') ' + 'for componentType:' + componentType);
  }
  return all[0];
},

/**
...
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.scryRenderedDOMComponentsWithClass"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>scryRenderedDOMComponentsWithClass (root, classNames)](#apidoc.element.react-dom.ReactTestUtils.scryRenderedDOMComponentsWithClass)
- description and source-code
```javascript
scryRenderedDOMComponentsWithClass = function (root, classNames) {
  return ReactTestUtils.findAllInRenderedTree(root, function (inst) {
    if (ReactTestUtils.isDOMComponent(inst)) {
      var className = inst.className;
      if (typeof className !== 'string') {
        // SVG, probably.
        className = inst.getAttribute('class') || '';
      }
      var classList = className.split(/\s+/);

      if (!Array.isArray(classNames)) {
        !(classNames !== undefined) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'TestUtils.scryRenderedDOMComponentsWithClass
 expects a className as a second argument.') : _prodInvariant('11') : void 0;
        classNames = classNames.split(/\s+/);
      }
      return classNames.every(function (name) {
        return classList.indexOf(name) !== -1;
      });
    }
    return false;
  });
}
```
- example usage
```shell
...
/**
 * Like scryRenderedDOMComponentsWithClass but expects there to be one result,
 * and returns that one result, or throws exception if there is any other
 * number of matches besides one.
 * @return {!ReactDOMComponent} The one match.
 */
findRenderedDOMComponentWithClass: function (root, className) {
  var all = ReactTestUtils.scryRenderedDOMComponentsWithClass(root, className);
  if (all.length !== 1) {
    throw new Error('Did not find exactly one match (found: ' + all.length + ') ' + 'for class:' + className);
  }
  return all[0];
},

/**
...
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.scryRenderedDOMComponentsWithTag"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>scryRenderedDOMComponentsWithTag (root, tagName)](#apidoc.element.react-dom.ReactTestUtils.scryRenderedDOMComponentsWithTag)
- description and source-code
```javascript
scryRenderedDOMComponentsWithTag = function (root, tagName) {
  return ReactTestUtils.findAllInRenderedTree(root, function (inst) {
    return ReactTestUtils.isDOMComponent(inst) && inst.tagName.toUpperCase() === tagName.toUpperCase();
  });
}
```
- example usage
```shell
...
/**
 * Like scryRenderedDOMComponentsWithTag but expects there to be one result,
 * and returns that one result, or throws exception if there is any other
 * number of matches besides one.
 * @return {!ReactDOMComponent} The one match.
 */
findRenderedDOMComponentWithTag: function (root, tagName) {
  var all = ReactTestUtils.scryRenderedDOMComponentsWithTag(root, tagName);
  if (all.length !== 1) {
    throw new Error('Did not find exactly one match (found: ' + all.length + ') ' + 'for tag:' + tagName);
  }
  return all[0];
},

/**
...
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.simulateNativeEventOnDOMComponent"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>simulateNativeEventOnDOMComponent (topLevelType, comp, fakeNativeEvent)](#apidoc.element.react-dom.ReactTestUtils.simulateNativeEventOnDOMComponent)
- description and source-code
```javascript
simulateNativeEventOnDOMComponent = function (topLevelType, comp, fakeNativeEvent) {
  ReactTestUtils.simulateNativeEventOnNode(topLevelType, findDOMNode(comp), fakeNativeEvent);
}
```
- example usage
```shell
...
 */

function makeNativeSimulator(eventType) {
  return function (domComponentOrNode, nativeEventData) {
    var fakeNativeEvent = new Event(eventType);
    _assign(fakeNativeEvent, nativeEventData);
    if (ReactTestUtils.isDOMComponent(domComponentOrNode)) {
      ReactTestUtils.simulateNativeEventOnDOMComponent(eventType, domComponentOrNode, fakeNativeEvent);
    } else if (domComponentOrNode.tagName) {
      // Will allow on actual dom nodes.
      ReactTestUtils.simulateNativeEventOnNode(eventType, domComponentOrNode, fakeNativeEvent);
    }
  };
}
...
```

#### <a name="apidoc.element.react-dom.ReactTestUtils.simulateNativeEventOnNode"></a>[function <span class="apidocSignatureSpan">react-dom.ReactTestUtils.</span>simulateNativeEventOnNode (topLevelType, node, fakeNativeEvent)](#apidoc.element.react-dom.ReactTestUtils.simulateNativeEventOnNode)
- description and source-code
```javascript
simulateNativeEventOnNode = function (topLevelType, node, fakeNativeEvent) {
  fakeNativeEvent.target = node;
  ReactBrowserEventEmitter.ReactEventListener.dispatchEvent(topLevelType, fakeNativeEvent);
}
```
- example usage
```shell
...
 * Simulates a top level event being dispatched from a raw event that occurred
 * on the 'ReactDOMComponent' 'comp'.
 * @param {Object} topLevelType A type from 'EventConstants.topLevelTypes'.
 * @param {!ReactDOMComponent} comp
 * @param {?Event} fakeNativeEvent Fake native event to use in SyntheticEvent.
 */
simulateNativeEventOnDOMComponent: function (topLevelType, comp, fakeNativeEvent) {
  ReactTestUtils.simulateNativeEventOnNode(topLevelType, findDOMNode(comp), fakeNativeEvent);
},

nativeTouchData: function (x, y) {
  return {
    touches: [{ pageX: x, pageY: y }]
  };
},
...
```



# <a name="apidoc.module.react-dom.ReactUpdateQueue"></a>[module react-dom.ReactUpdateQueue](#apidoc.module.react-dom.ReactUpdateQueue)

#### <a name="apidoc.element.react-dom.ReactUpdateQueue.enqueueCallback"></a>[function <span class="apidocSignatureSpan">react-dom.ReactUpdateQueue.</span>enqueueCallback (publicInstance, callback, callerName)](#apidoc.element.react-dom.ReactUpdateQueue.enqueueCallback)
- description and source-code
```javascript
enqueueCallback = function (publicInstance, callback, callerName) {
  ReactUpdateQueue.validateCallback(callback, callerName);
  var internalInstance = getInternalInstanceReadyForUpdate(publicInstance);

  // Previously we would throw an error if we didn't have an internal
  // instance. Since we want to make it a no-op instead, we mirror the same
  // behavior we have in other enqueue* methods.
  // We also need to ignore callbacks in componentWillMount. See
  // enqueueUpdates.
  if (!internalInstance) {
    return null;
  }

  if (internalInstance._pendingCallbacks) {
    internalInstance._pendingCallbacks.push(callback);
  } else {
    internalInstance._pendingCallbacks = [callback];
  }
  // TODO: The callback here is ignored when setState is called from
  // componentWillMount. Either fix it or disallow doing so completely in
  // favor of getInitialState. Alternatively, we can disallow
  // componentWillMount during server-side rendering.
  enqueueUpdate(internalInstance);
}
```
- example usage
```shell
...
 * @param {?function} callback Called after state is updated.
 * @internal
 */


ReactServerUpdateQueue.prototype.enqueueCallback = function enqueueCallback(publicInstance, callback, callerName) {
  if (this.transaction.isInTransaction()) {
    ReactUpdateQueue.enqueueCallback(publicInstance, callback, callerName);
  }
};

/**
 * Forces an update. This should only be invoked when it is known with
 * certainty that we are **not** in a DOM transaction.
 *
...
```

#### <a name="apidoc.element.react-dom.ReactUpdateQueue.enqueueCallbackInternal"></a>[function <span class="apidocSignatureSpan">react-dom.ReactUpdateQueue.</span>enqueueCallbackInternal (internalInstance, callback)](#apidoc.element.react-dom.ReactUpdateQueue.enqueueCallbackInternal)
- description and source-code
```javascript
enqueueCallbackInternal = function (internalInstance, callback) {
  if (internalInstance._pendingCallbacks) {
    internalInstance._pendingCallbacks.push(callback);
  } else {
    internalInstance._pendingCallbacks = [callback];
  }
  enqueueUpdate(internalInstance);
}
```
- example usage
```shell
...
 * @param {DOMElement} container container to render into
 * @param {?function} callback function triggered on completion
 */
_updateRootComponent: function (prevComponent, nextElement, nextContext, container, callback) {
  ReactMount.scrollMonitor(container, function () {
    ReactUpdateQueue.enqueueElementInternal(prevComponent, nextElement, nextContext);
    if (callback) {
      ReactUpdateQueue.enqueueCallbackInternal(prevComponent, callback);
    }
  });

  return prevComponent;
},

/**
...
```

#### <a name="apidoc.element.react-dom.ReactUpdateQueue.enqueueElementInternal"></a>[function <span class="apidocSignatureSpan">react-dom.ReactUpdateQueue.</span>enqueueElementInternal (internalInstance, nextElement, nextContext)](#apidoc.element.react-dom.ReactUpdateQueue.enqueueElementInternal)
- description and source-code
```javascript
enqueueElementInternal = function (internalInstance, nextElement, nextContext) {
  internalInstance._pendingElement = nextElement;
  // TODO: introduce _pendingContext instead of setting it directly.
  internalInstance._context = nextContext;
  enqueueUpdate(internalInstance);
}
```
- example usage
```shell
...
 * @param {ReactComponent} prevComponent component instance already in the DOM
 * @param {ReactElement} nextElement component instance to render
 * @param {DOMElement} container container to render into
 * @param {?function} callback function triggered on completion
 */
_updateRootComponent: function (prevComponent, nextElement, nextContext, container, callback) {
  ReactMount.scrollMonitor(container, function () {
    ReactUpdateQueue.enqueueElementInternal(prevComponent, nextElement, nextContext);
    if (callback) {
      ReactUpdateQueue.enqueueCallbackInternal(prevComponent, callback);
    }
  });

  return prevComponent;
},
...
```

#### <a name="apidoc.element.react-dom.ReactUpdateQueue.enqueueForceUpdate"></a>[function <span class="apidocSignatureSpan">react-dom.ReactUpdateQueue.</span>enqueueForceUpdate (publicInstance)](#apidoc.element.react-dom.ReactUpdateQueue.enqueueForceUpdate)
- description and source-code
```javascript
enqueueForceUpdate = function (publicInstance) {
  var internalInstance = getInternalInstanceReadyForUpdate(publicInstance, 'forceUpdate');

  if (!internalInstance) {
    return;
  }

  internalInstance._pendingForceUpdate = true;

  enqueueUpdate(internalInstance);
}
```
- example usage
```shell
...
 * @param {ReactClass} publicInstance The instance that should rerender.
 * @internal
 */


ReactServerUpdateQueue.prototype.enqueueForceUpdate = function enqueueForceUpdate(publicInstance) {
  if (this.transaction.isInTransaction()) {
    ReactUpdateQueue.enqueueForceUpdate(publicInstance);
  } else {
    warnNoop(publicInstance, 'forceUpdate');
  }
};

/**
 * Replaces all of the state. Always use this or 'setState' to mutate state.
...
```

#### <a name="apidoc.element.react-dom.ReactUpdateQueue.enqueueReplaceState"></a>[function <span class="apidocSignatureSpan">react-dom.ReactUpdateQueue.</span>enqueueReplaceState (publicInstance, completeState, callback)](#apidoc.element.react-dom.ReactUpdateQueue.enqueueReplaceState)
- description and source-code
```javascript
enqueueReplaceState = function (publicInstance, completeState, callback) {
  var internalInstance = getInternalInstanceReadyForUpdate(publicInstance, 'replaceState');

  if (!internalInstance) {
    return;
  }

  internalInstance._pendingStateQueue = [completeState];
  internalInstance._pendingReplaceState = true;

  // Future-proof 15.5
  if (callback !== undefined && callback !== null) {
    ReactUpdateQueue.validateCallback(callback, 'replaceState');
    if (internalInstance._pendingCallbacks) {
      internalInstance._pendingCallbacks.push(callback);
    } else {
      internalInstance._pendingCallbacks = [callback];
    }
  }

  enqueueUpdate(internalInstance);
}
```
- example usage
```shell
...
 * @param {object|function} completeState Next state.
 * @internal
 */


ReactServerUpdateQueue.prototype.enqueueReplaceState = function enqueueReplaceState(publicInstance, completeState) {
  if (this.transaction.isInTransaction()) {
    ReactUpdateQueue.enqueueReplaceState(publicInstance, completeState);
  } else {
    warnNoop(publicInstance, 'replaceState');
  }
};

/**
 * Sets a subset of the state. This only exists because _pendingState is
...
```

#### <a name="apidoc.element.react-dom.ReactUpdateQueue.enqueueSetState"></a>[function <span class="apidocSignatureSpan">react-dom.ReactUpdateQueue.</span>enqueueSetState (publicInstance, partialState)](#apidoc.element.react-dom.ReactUpdateQueue.enqueueSetState)
- description and source-code
```javascript
enqueueSetState = function (publicInstance, partialState) {
  if (process.env.NODE_ENV !== 'production') {
    ReactInstrumentation.debugTool.onSetState();
    process.env.NODE_ENV !== 'production' ? warning(partialState != null, 'setState(...): You passed an undefined or null state
object; ' + 'instead, use forceUpdate().') : void 0;
  }

  var internalInstance = getInternalInstanceReadyForUpdate(publicInstance, 'setState');

  if (!internalInstance) {
    return;
  }

  var queue = internalInstance._pendingStateQueue || (internalInstance._pendingStateQueue = []);
  queue.push(partialState);

  enqueueUpdate(internalInstance);
}
```
- example usage
```shell
...
   * @param {object|function} partialState Next partial state to be merged with state.
   * @internal
   */


  ReactServerUpdateQueue.prototype.enqueueSetState = function enqueueSetState(publicInstance, partialState) {
    if (this.transaction.isInTransaction()) {
      ReactUpdateQueue.enqueueSetState(publicInstance, partialState);
    } else {
      warnNoop(publicInstance, 'setState');
    }
  };

  return ReactServerUpdateQueue;
}();
...
```

#### <a name="apidoc.element.react-dom.ReactUpdateQueue.isMounted"></a>[function <span class="apidocSignatureSpan">react-dom.ReactUpdateQueue.</span>isMounted (publicInstance)](#apidoc.element.react-dom.ReactUpdateQueue.isMounted)
- description and source-code
```javascript
isMounted = function (publicInstance) {
  if (process.env.NODE_ENV !== 'production') {
    var owner = ReactCurrentOwner.current;
    if (owner !== null) {
      process.env.NODE_ENV !== 'production' ? warning(owner._warnedAboutRefsInRender, '%s is accessing isMounted inside its render
() function. ' + 'render() should be a pure function of props and state. It should ' + 'never access something that requires stale
 data from the previous ' + 'render, such as refs. Move this logic to componentDidMount and ' + 'componentDidUpdate instead.', owner
.getName() || 'A component') : void 0;
      owner._warnedAboutRefsInRender = true;
    }
  }
  var internalInstance = ReactInstanceMap.get(publicInstance);
  if (internalInstance) {
    // During componentWillMount and render this will still be null but after
    // that will always render to something. At least for now. So we can use
    // this hack.
    return !!internalInstance._renderedComponent;
  } else {
    return false;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactUpdateQueue.validateCallback"></a>[function <span class="apidocSignatureSpan">react-dom.ReactUpdateQueue.</span>validateCallback (callback, callerName)](#apidoc.element.react-dom.ReactUpdateQueue.validateCallback)
- description and source-code
```javascript
validateCallback = function (callback, callerName) {
  !(!callback || typeof callback === 'function') ? process.env.NODE_ENV !== 'production' ? invariant(false, '%s(...): Expected the
 last optional 'callback' argument to be a function. Instead received: %s.', callerName, formatUnexpectedArgument(callback)) : _prodInvariant
('122', callerName, formatUnexpectedArgument(callback)) : void 0;
}
```
- example usage
```shell
...
   */
  renderSubtreeIntoContainer: function (parentComponent, nextElement, container, callback) {
!(parentComponent != null && ReactInstanceMap.has(parentComponent)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '
parentComponent must be a valid React Component') : _prodInvariant('38') : void 0;
return ReactMount._renderSubtreeIntoContainer(parentComponent, nextElement, container, callback);
  },

  _renderSubtreeIntoContainer: function (parentComponent, nextElement, container, callback) {
ReactUpdateQueue.validateCallback(callback, 'ReactDOM.render');
!React.isValidElement(nextElement) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'ReactDOM.render(): Invalid component
 element.%s', typeof nextElement === 'string' ? ' Instead of passing a string like\'div\', pass ' + 'React.createElement(\'div\') or <div />.' : typeof nextElement === 'function' ? ' Instead of passing a class like Foo, pass ' + 'React.createElement(Foo) or <Foo />.' :
// Check if it quacks like an element
nextElement != null && nextElement.props !== undefined ? ' This may be caused by unintentionally loading two independent ' + 'copies
 of React.' : '') : _prodInvariant('39', typeof nextElement === 'string' ? ' Instead of passing a string like\'div\', pass ' + 'React.createElement(\'div\') or <div />.' : typeof nextElement === 'function' ? ' Instead of passing a class like Foo, pass ' + 'React.createElement(Foo) or <Foo />.' : nextElement != null && nextElement.props !== undefined ? ' This may be caused by unintentionally loading two independent ' + 'copies of React.' : '') : void 0;

process.env.NODE_ENV !== 'production' ? warning(!container || !container.tagName || container.tagName.toUpperCase() !== 'BODY', '
render(): Rendering components directly into document.body is ' + 'discouraged, since its children are often manipulated by third
-party ' + 'scripts and browser extensions. This may lead to subtle ' + 'reconciliation issues. Try rendering into a container element
 created ' + 'for your app.') : void 0;

var nextWrappedElement = React.createElement(TopLevelWrapper, { child: nextElement });
...
```



# <a name="apidoc.module.react-dom.ReactUpdates"></a>[module react-dom.ReactUpdates](#apidoc.module.react-dom.ReactUpdates)

#### <a name="apidoc.element.react-dom.ReactUpdates.ReactReconcileTransaction"></a>[function <span class="apidocSignatureSpan">react-dom.ReactUpdates.</span>ReactReconcileTransaction (useCreateElement)](#apidoc.element.react-dom.ReactUpdates.ReactReconcileTransaction)
- description and source-code
```javascript
function ReactReconcileTransaction(useCreateElement) {
  this.reinitializeTransaction();
  // Only server-side rendering really needs this option (see
  // 'ReactServerRendering'), but server-side uses
  // 'ReactServerRenderingTransaction' instead. This option is here so that it's
  // accessible and defaults to false when 'ReactDOMComponent' and
  // 'ReactDOMTextComponent' checks it in 'mountComponent'.'
  this.renderToStaticMarkup = false;
  this.reactMountReady = CallbackQueue.getPooled(null);
  this.useCreateElement = useCreateElement;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ReactUpdates.asap"></a>[function <span class="apidocSignatureSpan">react-dom.ReactUpdates.</span>asap (callback, context)](#apidoc.element.react-dom.ReactUpdates.asap)
- description and source-code
```javascript
function asap(callback, context) {
  !batchingStrategy.isBatchingUpdates ? process.env.NODE_ENV !== 'production' ? invariant(false, 'ReactUpdates.asap: Can\'t enqueue
 an asap callback in a context whereupdates are not being batched.') : _prodInvariant('125') : void 0;
  asapCallbackQueue.enqueue(callback, context);
  asapEnqueued = true;
}
```
- example usage
```shell
...
  var props = this._currentElement.props;

  var returnValue = LinkedValueUtils.executeOnChange(props, event);

  // Here we use asap to wait until all updates have propagated, which
  // is important when using controlled components within layers:
  // https://github.com/facebook/react/issues/1698
  ReactUpdates.asap(forceUpdateIfMounted, this);

  var name = props.name;
  if (props.type === 'radio' && name != null) {
var rootNode = ReactDOMComponentTree.getNodeFromInstance(this);
var queryRoot = rootNode;

while (queryRoot.parentNode) {
...
```

#### <a name="apidoc.element.react-dom.ReactUpdates.batchedUpdates"></a>[function <span class="apidocSignatureSpan">react-dom.ReactUpdates.</span>batchedUpdates (callback, a, b, c, d, e)](#apidoc.element.react-dom.ReactUpdates.batchedUpdates)
- description and source-code
```javascript
function batchedUpdates(callback, a, b, c, d, e) {
  ensureInjected();
  return batchingStrategy.batchedUpdates(callback, a, b, c, d, e);
}
```
- example usage
```shell
...
  //
  // Batching is necessary here in order to ensure that all event handlers run
  // before the next rerender (including event handlers attached to ancestor
  // elements instead of directly on the input). Without this, controlled
  // components don't work properly in conjunction with event bubbling because
  // the component is rerendered and the value reverted before all the event
  // handlers can run. See https://github.com/facebook/react/issues/708.
  ReactUpdates.batchedUpdates(runEventInBatch, event);
}

function runEventInBatch(event) {
  EventPluginHub.enqueueEvents(event);
  EventPluginHub.processEventQueue(false);
}
...
```

#### <a name="apidoc.element.react-dom.ReactUpdates.enqueueUpdate"></a>[function <span class="apidocSignatureSpan">react-dom.ReactUpdates.</span>enqueueUpdate (component)](#apidoc.element.react-dom.ReactUpdates.enqueueUpdate)
- description and source-code
```javascript
function enqueueUpdate(component) {
  ensureInjected();

  // Various parts of our code (such as ReactCompositeComponent's
  // _renderValidatedComponent) assume that calls to render aren't nested;
  // verify that that's the case. (This is called by each top-level update
  // function, like setState, forceUpdate, etc.; creation and
  // destruction of top-level components is guarded in ReactMount.)

  if (!batchingStrategy.isBatchingUpdates) {
    batchingStrategy.batchedUpdates(enqueueUpdate, component);
    return;
  }

  dirtyComponents.push(component);
  if (component._updateBatchNumber == null) {
    component._updateBatchNumber = updateBatchNumber + 1;
  }
}
```
- example usage
```shell
...
var ReactInstrumentation = require('./ReactInstrumentation');
var ReactUpdates = require('./ReactUpdates');

var invariant = require('fbjs/lib/invariant');
var warning = require('fbjs/lib/warning');

function enqueueUpdate(internalInstance) {
ReactUpdates.enqueueUpdate(internalInstance);
}

function formatUnexpectedArgument(arg) {
var type = typeof arg;
if (type !== 'object') {
  return type;
}
...
```

#### <a name="apidoc.element.react-dom.ReactUpdates.flushBatchedUpdates"></a>[function <span class="apidocSignatureSpan">react-dom.ReactUpdates.</span>flushBatchedUpdates ()](#apidoc.element.react-dom.ReactUpdates.flushBatchedUpdates)
- description and source-code
```javascript
flushBatchedUpdates = function () {
  // ReactUpdatesFlushTransaction's wrappers will clear the dirtyComponents
  // array and perform any updates enqueued by mount-ready handlers (i.e.,
  // componentDidUpdate) but we need to check here too in order to catch
  // updates enqueued by setState callbacks and asap calls.
  while (dirtyComponents.length || asapEnqueued) {
    if (dirtyComponents.length) {
      var transaction = ReactUpdatesFlushTransaction.getPooled();
      transaction.perform(runBatchedUpdates, null, transaction);
      ReactUpdatesFlushTransaction.release(transaction);
    }

    if (asapEnqueued) {
      asapEnqueued = false;
      var queue = asapCallbackQueue;
      asapCallbackQueue = CallbackQueue.getPooled();
      queue.notifyAll();
      CallbackQueue.release(queue);
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ResponderEventPlugin"></a>[module react-dom.ResponderEventPlugin](#apidoc.module.react-dom.ResponderEventPlugin)

#### <a name="apidoc.element.react-dom.ResponderEventPlugin._getResponderID"></a>[function <span class="apidocSignatureSpan">react-dom.ResponderEventPlugin.</span>_getResponderID ()](#apidoc.element.react-dom.ResponderEventPlugin._getResponderID)
- description and source-code
```javascript
_getResponderID = function () {
  return responderInst ? responderInst._rootNodeID : null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ResponderEventPlugin.extractEvents"></a>[function <span class="apidocSignatureSpan">react-dom.ResponderEventPlugin.</span>extractEvents (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.ResponderEventPlugin.extractEvents)
- description and source-code
```javascript
extractEvents = function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  if (isStartish(topLevelType)) {
    trackedTouchCount += 1;
  } else if (isEndish(topLevelType)) {
    if (trackedTouchCount >= 0) {
      trackedTouchCount -= 1;
    } else {
      console.error('Ended a touch event which was not counted in 'trackedTouchCount'.');
      return null;
    }
  }

  ResponderTouchHistoryStore.recordTouchTrack(topLevelType, nativeEvent);

  var extracted = canTriggerTransfer(topLevelType, targetInst, nativeEvent) ? setResponderAndExtractTransfer(topLevelType, targetInst
, nativeEvent, nativeEventTarget) : null;
  // Responder may or may not have transferred on a new touch start/move.
  // Regardless, whoever is the responder after any potential transfer, we
  // direct all touch start/move/ends to them in the form of
  // 'onResponderMove/Start/End'. These will be called for *every* additional
  // finger that move/start/end, dispatched directly to whoever is the
  // current responder at that moment, until the responder is "released".
  //
  // These multiple individual change touch events are are always bookended
  // by 'onResponderGrant', and one of
  // ('onResponderRelease/onResponderTerminate').
  var isResponderTouchStart = responderInst && isStartish(topLevelType);
  var isResponderTouchMove = responderInst && isMoveish(topLevelType);
  var isResponderTouchEnd = responderInst && isEndish(topLevelType);
  var incrementalTouch = isResponderTouchStart ? eventTypes.responderStart : isResponderTouchMove ? eventTypes.responderMove : isResponderTouchEnd
 ? eventTypes.responderEnd : null;

  if (incrementalTouch) {
    var gesture = ResponderSyntheticEvent.getPooled(incrementalTouch, responderInst, nativeEvent, nativeEventTarget);
    gesture.touchHistory = ResponderTouchHistoryStore.touchHistory;
    EventPropagators.accumulateDirectDispatches(gesture);
    extracted = accumulate(extracted, gesture);
  }

  var isResponderTerminate = responderInst && topLevelType === 'topTouchCancel';
  var isResponderRelease = responderInst && !isResponderTerminate && isEndish(topLevelType) && noResponderTouches(nativeEvent);
  var finalTouch = isResponderTerminate ? eventTypes.responderTerminate : isResponderRelease ? eventTypes.responderRelease : null
;
  if (finalTouch) {
    var finalEvent = ResponderSyntheticEvent.getPooled(finalTouch, responderInst, nativeEvent, nativeEventTarget);
    finalEvent.touchHistory = ResponderTouchHistoryStore.touchHistory;
    EventPropagators.accumulateDirectDispatches(finalEvent);
    extracted = accumulate(extracted, finalEvent);
    changeResponder(null);
  }

  var numberActiveTouches = ResponderTouchHistoryStore.touchHistory.numberActiveTouches;
  if (ResponderEventPlugin.GlobalInteractionHandler && numberActiveTouches !== previousActiveTouches) {
    ResponderEventPlugin.GlobalInteractionHandler.onChange(numberActiveTouches);
  }
  previousActiveTouches = numberActiveTouches;

  return extracted;
}
```
- example usage
```shell
...
extractEvents: function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  var events;
  var plugins = EventPluginRegistry.plugins;
  for (var i = 0; i < plugins.length; i++) {
    // Not every plugin in the ordering may be loaded at runtime.
    var possiblePlugin = plugins[i];
    if (possiblePlugin) {
      var extractedEvents = possiblePlugin.extractEvents(topLevelType, targetInst, nativeEvent, nativeEventTarget);
      if (extractedEvents) {
        events = accumulateInto(events, extractedEvents);
      }
    }
  }
  return events;
},
...
```



# <a name="apidoc.module.react-dom.ResponderSyntheticEvent"></a>[module react-dom.ResponderSyntheticEvent](#apidoc.module.react-dom.ResponderSyntheticEvent)

#### <a name="apidoc.element.react-dom.ResponderSyntheticEvent.ResponderSyntheticEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>ResponderSyntheticEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.ResponderSyntheticEvent.ResponderSyntheticEvent)
- description and source-code
```javascript
function ResponderSyntheticEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.ResponderSyntheticEvent.augmentClass"></a>[function <span class="apidocSignatureSpan">react-dom.ResponderSyntheticEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.ResponderSyntheticEvent.augmentClass)
- description and source-code
```javascript
augmentClass = function (Class, Interface) {
  var Super = this;

  var E = function () {};
  E.prototype = Super.prototype;
  var prototype = new E();

  _assign(prototype, Class.prototype);
  Class.prototype = prototype;
  Class.prototype.constructor = Class;

  Class.Interface = _assign({}, Super.Interface, Interface);
  Class.augmentClass = Super.augmentClass;

  PooledClass.addPoolingTo(Class, PooledClass.fourArgumentPooler);
}
```
- example usage
```shell
...
 * @param {object} nativeEvent Native event.
 * @extends {SyntheticEvent}
 */
function ResponderSyntheticEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}

SyntheticEvent.augmentClass(ResponderSyntheticEvent, ResponderEventInterface);

module.exports = ResponderSyntheticEvent;
...
```

#### <a name="apidoc.element.react-dom.ResponderSyntheticEvent.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.ResponderSyntheticEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.ResponderSyntheticEvent.getPooled)
- description and source-code
```javascript
getPooled = function (a1, a2, a3, a4) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2, a3, a4);
    return instance;
  } else {
    return new Klass(a1, a2, a3, a4);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.ResponderSyntheticEvent.release"></a>[function <span class="apidocSignatureSpan">react-dom.ResponderSyntheticEvent.</span>release (instance)](#apidoc.element.react-dom.ResponderSyntheticEvent.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.ResponderSyntheticEvent.prototype"></a>[module react-dom.ResponderSyntheticEvent.prototype](#apidoc.module.react-dom.ResponderSyntheticEvent.prototype)

#### <a name="apidoc.element.react-dom.ResponderSyntheticEvent.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react-dom.ResponderSyntheticEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.ResponderSyntheticEvent.prototype.constructor)
- description and source-code
```javascript
function ResponderSyntheticEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.ResponderTouchHistoryStore"></a>[module react-dom.ResponderTouchHistoryStore](#apidoc.module.react-dom.ResponderTouchHistoryStore)

#### <a name="apidoc.element.react-dom.ResponderTouchHistoryStore.recordTouchTrack"></a>[function <span class="apidocSignatureSpan">react-dom.ResponderTouchHistoryStore.</span>recordTouchTrack (topLevelType, nativeEvent)](#apidoc.element.react-dom.ResponderTouchHistoryStore.recordTouchTrack)
- description and source-code
```javascript
recordTouchTrack = function (topLevelType, nativeEvent) {
  if (isMoveish(topLevelType)) {
    nativeEvent.changedTouches.forEach(recordTouchMove);
  } else if (isStartish(topLevelType)) {
    nativeEvent.changedTouches.forEach(recordTouchStart);
    touchHistory.numberActiveTouches = nativeEvent.touches.length;
    if (touchHistory.numberActiveTouches === 1) {
      touchHistory.indexOfSingleActiveTouch = nativeEvent.touches[0].identifier;
    }
  } else if (isEndish(topLevelType)) {
    nativeEvent.changedTouches.forEach(recordTouchEnd);
    touchHistory.numberActiveTouches = nativeEvent.touches.length;
    if (touchHistory.numberActiveTouches === 1) {
      for (var i = 0; i < touchBank.length; i++) {
        var touchTrackToCheck = touchBank[i];
        if (touchTrackToCheck != null && touchTrackToCheck.touchActive) {
          touchHistory.indexOfSingleActiveTouch = i;
          break;
        }
      }
      if (process.env.NODE_ENV !== 'production') {
        var activeRecord = touchBank[touchHistory.indexOfSingleActiveTouch];
        process.env.NODE_ENV !== 'production' ? warning(activeRecord != null && activeRecord.touchActive, 'Cannot find single active
 touch.') : void 0;
      }
    }
  }
}
```
- example usage
```shell
...
    trackedTouchCount -= 1;
  } else {
    console.error('Ended a touch event which was not counted in 'trackedTouchCount'.');
    return null;
  }
}

ResponderTouchHistoryStore.recordTouchTrack(topLevelType, nativeEvent);

var extracted = canTriggerTransfer(topLevelType, targetInst, nativeEvent) ? setResponderAndExtractTransfer(topLevelType, targetInst
, nativeEvent, nativeEventTarget) : null;
// Responder may or may not have transferred on a new touch start/move.
// Regardless, whoever is the responder after any potential transfer, we
// direct all touch start/move/ends to them in the form of
// 'onResponderMove/Start/End'. These will be called for *every* additional
// finger that move/start/end, dispatched directly to whoever is the
...
```



# <a name="apidoc.module.react-dom.SelectEventPlugin"></a>[module react-dom.SelectEventPlugin](#apidoc.module.react-dom.SelectEventPlugin)

#### <a name="apidoc.element.react-dom.SelectEventPlugin.didPutListener"></a>[function <span class="apidocSignatureSpan">react-dom.SelectEventPlugin.</span>didPutListener (inst, registrationName, listener)](#apidoc.element.react-dom.SelectEventPlugin.didPutListener)
- description and source-code
```javascript
didPutListener = function (inst, registrationName, listener) {
  if (registrationName === 'onSelect') {
    hasListener = true;
  }
}
```
- example usage
```shell
...

  var key = getDictionaryKey(inst);
  var bankForRegistrationName = listenerBank[registrationName] || (listenerBank[registrationName] = {});
  bankForRegistrationName[key] = listener;

  var PluginModule = EventPluginRegistry.registrationNameModules[registrationName];
  if (PluginModule && PluginModule.didPutListener) {
    PluginModule.didPutListener(inst, registrationName, listener);
  }
},

/**
 * @param {object} inst The instance, which is the source of events.
 * @param {string} registrationName Name of listener (e.g. 'onClick').
 * @return {?function} The stored callback.
...
```

#### <a name="apidoc.element.react-dom.SelectEventPlugin.extractEvents"></a>[function <span class="apidocSignatureSpan">react-dom.SelectEventPlugin.</span>extractEvents (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SelectEventPlugin.extractEvents)
- description and source-code
```javascript
extractEvents = function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  if (!hasListener) {
    return null;
  }

  var targetNode = targetInst ? ReactDOMComponentTree.getNodeFromInstance(targetInst) : window;

  switch (topLevelType) {
    // Track the input node that has focus.
    case 'topFocus':
      if (isTextInputElement(targetNode) || targetNode.contentEditable === 'true') {
        activeElement = targetNode;
        activeElementInst = targetInst;
        lastSelection = null;
      }
      break;
    case 'topBlur':
      activeElement = null;
      activeElementInst = null;
      lastSelection = null;
      break;

    // Don't fire the event while the user is dragging. This matches the
    // semantics of the native select event.
    case 'topMouseDown':
      mouseDown = true;
      break;
    case 'topContextMenu':
    case 'topMouseUp':
      mouseDown = false;
      return constructSelectEvent(nativeEvent, nativeEventTarget);

    // Chrome and IE fire non-standard event when selection is changed (and
    // sometimes when it hasn't). IE's event fires out of order with respect
    // to key and input events on deletion, so we discard it.
    //
    // Firefox doesn't support selectionchange, so check selection status
    // after each key entry. The selection changes after keydown and before
    // keyup, but we check on keydown as well in the case of holding down a
    // key, when multiple keydown events are fired but only one keyup is.
    // This is also our approach for IE handling, for the reason above.
    case 'topSelectionChange':
      if (skipSelectionChangeEvent) {
        break;
      }
    // falls through
    case 'topKeyDown':
    case 'topKeyUp':
      return constructSelectEvent(nativeEvent, nativeEventTarget);
  }

  return null;
}
```
- example usage
```shell
...
extractEvents: function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  var events;
  var plugins = EventPluginRegistry.plugins;
  for (var i = 0; i < plugins.length; i++) {
    // Not every plugin in the ordering may be loaded at runtime.
    var possiblePlugin = plugins[i];
    if (possiblePlugin) {
      var extractedEvents = possiblePlugin.extractEvents(topLevelType, targetInst, nativeEvent, nativeEventTarget);
      if (extractedEvents) {
        events = accumulateInto(events, extractedEvents);
      }
    }
  }
  return events;
},
...
```



# <a name="apidoc.module.react-dom.SimpleEventPlugin"></a>[module react-dom.SimpleEventPlugin](#apidoc.module.react-dom.SimpleEventPlugin)

#### <a name="apidoc.element.react-dom.SimpleEventPlugin.didPutListener"></a>[function <span class="apidocSignatureSpan">react-dom.SimpleEventPlugin.</span>didPutListener (inst, registrationName, listener)](#apidoc.element.react-dom.SimpleEventPlugin.didPutListener)
- description and source-code
```javascript
didPutListener = function (inst, registrationName, listener) {
  // Mobile Safari does not fire properly bubble click events on
  // non-interactive elements, which means delegated click listeners do not
  // fire. The workaround for this bug involves attaching an empty click
  // listener on the target node.
  // http://www.quirksmode.org/blog/archives/2010/09/click_event_del.html
  if (registrationName === 'onClick' && !isInteractive(inst._tag)) {
    var key = getDictionaryKey(inst);
    var node = ReactDOMComponentTree.getNodeFromInstance(inst);
    if (!onClickListeners[key]) {
      onClickListeners[key] = EventListener.listen(node, 'click', emptyFunction);
    }
  }
}
```
- example usage
```shell
...

  var key = getDictionaryKey(inst);
  var bankForRegistrationName = listenerBank[registrationName] || (listenerBank[registrationName] = {});
  bankForRegistrationName[key] = listener;

  var PluginModule = EventPluginRegistry.registrationNameModules[registrationName];
  if (PluginModule && PluginModule.didPutListener) {
    PluginModule.didPutListener(inst, registrationName, listener);
  }
},

/**
 * @param {object} inst The instance, which is the source of events.
 * @param {string} registrationName Name of listener (e.g. 'onClick').
 * @return {?function} The stored callback.
...
```

#### <a name="apidoc.element.react-dom.SimpleEventPlugin.extractEvents"></a>[function <span class="apidocSignatureSpan">react-dom.SimpleEventPlugin.</span>extractEvents (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SimpleEventPlugin.extractEvents)
- description and source-code
```javascript
extractEvents = function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  var dispatchConfig = topLevelEventsToDispatchConfig[topLevelType];
  if (!dispatchConfig) {
    return null;
  }
  var EventConstructor;
  switch (topLevelType) {
    case 'topAbort':
    case 'topCanPlay':
    case 'topCanPlayThrough':
    case 'topDurationChange':
    case 'topEmptied':
    case 'topEncrypted':
    case 'topEnded':
    case 'topError':
    case 'topInput':
    case 'topInvalid':
    case 'topLoad':
    case 'topLoadedData':
    case 'topLoadedMetadata':
    case 'topLoadStart':
    case 'topPause':
    case 'topPlay':
    case 'topPlaying':
    case 'topProgress':
    case 'topRateChange':
    case 'topReset':
    case 'topSeeked':
    case 'topSeeking':
    case 'topStalled':
    case 'topSubmit':
    case 'topSuspend':
    case 'topTimeUpdate':
    case 'topVolumeChange':
    case 'topWaiting':
      // HTML Events
      // @see http://www.w3.org/TR/html5/index.html#events-0
      EventConstructor = SyntheticEvent;
      break;
    case 'topKeyPress':
      // Firefox creates a keypress event for function keys too. This removes
      // the unwanted keypress events. Enter is however both printable and
      // non-printable. One would expect Tab to be as well (but it isn't).
      if (getEventCharCode(nativeEvent) === 0) {
        return null;
      }
<span class="apidocCodeCommentSpan">    /* falls through */
</span>    case 'topKeyDown':
    case 'topKeyUp':
      EventConstructor = SyntheticKeyboardEvent;
      break;
    case 'topBlur':
    case 'topFocus':
      EventConstructor = SyntheticFocusEvent;
      break;
    case 'topClick':
      // Firefox creates a click event on right mouse clicks. This removes the
      // unwanted click events.
      if (nativeEvent.button === 2) {
        return null;
      }
    /* falls through */
    case 'topDoubleClick':
    case 'topMouseDown':
    case 'topMouseMove':
    case 'topMouseUp':
    // TODO: Disabled elements should not respond to mouse events
    /* falls through */
    case 'topMouseOut':
    case 'topMouseOver':
    case 'topContextMenu':
      EventConstructor = SyntheticMouseEvent;
      break;
    case 'topDrag':
    case 'topDragEnd':
    case 'topDragEnter':
    case 'topDragExit':
    case 'topDragLeave':
    case 'topDragOver':
    case 'topDragStart':
    case 'topDrop':
      EventConstructor = SyntheticDragEvent;
      break;
    case 'topTouchCancel':
    case 'topTouchEnd':
    case 'topTouchMove':
    case 'topTouchStart':
      EventConstructor = SyntheticTouchEvent;
      break;
    case 'topAnimationEnd':
    case 'topAnimationIteration':
    case 'topAnimationStart':
      EventConstructor = SyntheticAnimationEvent;
      break;
    case 'topTransitionEnd':
      EventConstructor = SyntheticTransitionEvent;
      break;
    case 'topScroll':
      EventConstructor = SyntheticUIEvent;
      break;
    case 'topWheel':
      EventConstructor = SyntheticWheelEvent;
      break;
    case 'topCopy':
    case 'topCut':
    case 'topPaste':
      EventConstructor = SyntheticClipboardEvent;
      break;
  }
  !EventConstructor ? process.env.NODE_ENV !== 'production' ? invariant(false, 'SimpleEventPlugin: Unhandled event type, '%s'.',
topLevelType) : _prodInvariant('86', topLevelType) : void 0;
  var event = EventConstructor.getPooled(dispatchConfig, targetInst, nativeEvent, nativeEventTarget);
  EventPropagators.accumulateTwoPhaseDispatches(event);
  return event;
}
```
- example usage
```shell
...
extractEvents: function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  var events;
  var plugins = EventPluginRegistry.plugins;
  for (var i = 0; i < plugins.length; i++) {
    // Not every plugin in the ordering may be loaded at runtime.
    var possiblePlugin = plugins[i];
    if (possiblePlugin) {
      var extractedEvents = possiblePlugin.extractEvents(topLevelType, targetInst, nativeEvent, nativeEventTarget);
      if (extractedEvents) {
        events = accumulateInto(events, extractedEvents);
      }
    }
  }
  return events;
},
...
```

#### <a name="apidoc.element.react-dom.SimpleEventPlugin.willDeleteListener"></a>[function <span class="apidocSignatureSpan">react-dom.SimpleEventPlugin.</span>willDeleteListener (inst, registrationName)](#apidoc.element.react-dom.SimpleEventPlugin.willDeleteListener)
- description and source-code
```javascript
willDeleteListener = function (inst, registrationName) {
  if (registrationName === 'onClick' && !isInteractive(inst._tag)) {
    var key = getDictionaryKey(inst);
    onClickListeners[key].remove();
    delete onClickListeners[key];
  }
}
```
- example usage
```shell
...
   *
   * @param {object} inst The instance, which is the source of events.
   * @param {string} registrationName Name of listener (e.g. 'onClick').
   */
  deleteListener: function (inst, registrationName) {
var PluginModule = EventPluginRegistry.registrationNameModules[registrationName];
if (PluginModule && PluginModule.willDeleteListener) {
  PluginModule.willDeleteListener(inst, registrationName);
}

var bankForRegistrationName = listenerBank[registrationName];
// TODO: This should never be null -- when is it?
if (bankForRegistrationName) {
  var key = getDictionaryKey(inst);
  delete bankForRegistrationName[key];
...
```



# <a name="apidoc.module.react-dom.SyntheticAnimationEvent"></a>[module react-dom.SyntheticAnimationEvent](#apidoc.module.react-dom.SyntheticAnimationEvent)

#### <a name="apidoc.element.react-dom.SyntheticAnimationEvent.SyntheticAnimationEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticAnimationEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticAnimationEvent.SyntheticAnimationEvent)
- description and source-code
```javascript
function SyntheticAnimationEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticAnimationEvent.augmentClass"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticAnimationEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticAnimationEvent.augmentClass)
- description and source-code
```javascript
augmentClass = function (Class, Interface) {
  var Super = this;

  var E = function () {};
  E.prototype = Super.prototype;
  var prototype = new E();

  _assign(prototype, Class.prototype);
  Class.prototype = prototype;
  Class.prototype.constructor = Class;

  Class.Interface = _assign({}, Super.Interface, Interface);
  Class.augmentClass = Super.augmentClass;

  PooledClass.addPoolingTo(Class, PooledClass.fourArgumentPooler);
}
```
- example usage
```shell
...
 * @param {object} nativeEvent Native event.
 * @extends {SyntheticEvent}
 */
function ResponderSyntheticEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}

SyntheticEvent.augmentClass(ResponderSyntheticEvent, ResponderEventInterface);

module.exports = ResponderSyntheticEvent;
...
```

#### <a name="apidoc.element.react-dom.SyntheticAnimationEvent.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticAnimationEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticAnimationEvent.getPooled)
- description and source-code
```javascript
getPooled = function (a1, a2, a3, a4) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2, a3, a4);
    return instance;
  } else {
    return new Klass(a1, a2, a3, a4);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.SyntheticAnimationEvent.release"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticAnimationEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticAnimationEvent.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.SyntheticAnimationEvent.prototype"></a>[module react-dom.SyntheticAnimationEvent.prototype](#apidoc.module.react-dom.SyntheticAnimationEvent.prototype)

#### <a name="apidoc.element.react-dom.SyntheticAnimationEvent.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticAnimationEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticAnimationEvent.prototype.constructor)
- description and source-code
```javascript
function SyntheticAnimationEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.SyntheticClipboardEvent"></a>[module react-dom.SyntheticClipboardEvent](#apidoc.module.react-dom.SyntheticClipboardEvent)

#### <a name="apidoc.element.react-dom.SyntheticClipboardEvent.SyntheticClipboardEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticClipboardEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticClipboardEvent.SyntheticClipboardEvent)
- description and source-code
```javascript
function SyntheticClipboardEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticClipboardEvent.augmentClass"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticClipboardEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticClipboardEvent.augmentClass)
- description and source-code
```javascript
augmentClass = function (Class, Interface) {
  var Super = this;

  var E = function () {};
  E.prototype = Super.prototype;
  var prototype = new E();

  _assign(prototype, Class.prototype);
  Class.prototype = prototype;
  Class.prototype.constructor = Class;

  Class.Interface = _assign({}, Super.Interface, Interface);
  Class.augmentClass = Super.augmentClass;

  PooledClass.addPoolingTo(Class, PooledClass.fourArgumentPooler);
}
```
- example usage
```shell
...
 * @param {object} nativeEvent Native event.
 * @extends {SyntheticEvent}
 */
function ResponderSyntheticEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}

SyntheticEvent.augmentClass(ResponderSyntheticEvent, ResponderEventInterface);

module.exports = ResponderSyntheticEvent;
...
```

#### <a name="apidoc.element.react-dom.SyntheticClipboardEvent.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticClipboardEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticClipboardEvent.getPooled)
- description and source-code
```javascript
getPooled = function (a1, a2, a3, a4) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2, a3, a4);
    return instance;
  } else {
    return new Klass(a1, a2, a3, a4);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.SyntheticClipboardEvent.release"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticClipboardEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticClipboardEvent.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.SyntheticClipboardEvent.prototype"></a>[module react-dom.SyntheticClipboardEvent.prototype](#apidoc.module.react-dom.SyntheticClipboardEvent.prototype)

#### <a name="apidoc.element.react-dom.SyntheticClipboardEvent.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticClipboardEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticClipboardEvent.prototype.constructor)
- description and source-code
```javascript
function SyntheticClipboardEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.SyntheticCompositionEvent"></a>[module react-dom.SyntheticCompositionEvent](#apidoc.module.react-dom.SyntheticCompositionEvent)

#### <a name="apidoc.element.react-dom.SyntheticCompositionEvent.SyntheticCompositionEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticCompositionEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticCompositionEvent.SyntheticCompositionEvent)
- description and source-code
```javascript
function SyntheticCompositionEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticCompositionEvent.augmentClass"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticCompositionEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticCompositionEvent.augmentClass)
- description and source-code
```javascript
augmentClass = function (Class, Interface) {
  var Super = this;

  var E = function () {};
  E.prototype = Super.prototype;
  var prototype = new E();

  _assign(prototype, Class.prototype);
  Class.prototype = prototype;
  Class.prototype.constructor = Class;

  Class.Interface = _assign({}, Super.Interface, Interface);
  Class.augmentClass = Super.augmentClass;

  PooledClass.addPoolingTo(Class, PooledClass.fourArgumentPooler);
}
```
- example usage
```shell
...
 * @param {object} nativeEvent Native event.
 * @extends {SyntheticEvent}
 */
function ResponderSyntheticEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}

SyntheticEvent.augmentClass(ResponderSyntheticEvent, ResponderEventInterface);

module.exports = ResponderSyntheticEvent;
...
```

#### <a name="apidoc.element.react-dom.SyntheticCompositionEvent.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticCompositionEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticCompositionEvent.getPooled)
- description and source-code
```javascript
getPooled = function (a1, a2, a3, a4) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2, a3, a4);
    return instance;
  } else {
    return new Klass(a1, a2, a3, a4);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.SyntheticCompositionEvent.release"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticCompositionEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticCompositionEvent.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.SyntheticCompositionEvent.prototype"></a>[module react-dom.SyntheticCompositionEvent.prototype](#apidoc.module.react-dom.SyntheticCompositionEvent.prototype)

#### <a name="apidoc.element.react-dom.SyntheticCompositionEvent.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticCompositionEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticCompositionEvent.prototype.constructor)
- description and source-code
```javascript
function SyntheticCompositionEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.SyntheticDragEvent"></a>[module react-dom.SyntheticDragEvent](#apidoc.module.react-dom.SyntheticDragEvent)

#### <a name="apidoc.element.react-dom.SyntheticDragEvent.SyntheticDragEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticDragEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticDragEvent.SyntheticDragEvent)
- description and source-code
```javascript
function SyntheticDragEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticMouseEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticDragEvent.augmentClass"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticDragEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticDragEvent.augmentClass)
- description and source-code
```javascript
augmentClass = function (Class, Interface) {
  var Super = this;

  var E = function () {};
  E.prototype = Super.prototype;
  var prototype = new E();

  _assign(prototype, Class.prototype);
  Class.prototype = prototype;
  Class.prototype.constructor = Class;

  Class.Interface = _assign({}, Super.Interface, Interface);
  Class.augmentClass = Super.augmentClass;

  PooledClass.addPoolingTo(Class, PooledClass.fourArgumentPooler);
}
```
- example usage
```shell
...
 * @param {object} nativeEvent Native event.
 * @extends {SyntheticEvent}
 */
function ResponderSyntheticEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}

SyntheticEvent.augmentClass(ResponderSyntheticEvent, ResponderEventInterface);

module.exports = ResponderSyntheticEvent;
...
```

#### <a name="apidoc.element.react-dom.SyntheticDragEvent.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticDragEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticDragEvent.getPooled)
- description and source-code
```javascript
getPooled = function (a1, a2, a3, a4) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2, a3, a4);
    return instance;
  } else {
    return new Klass(a1, a2, a3, a4);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.SyntheticDragEvent.release"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticDragEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticDragEvent.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.SyntheticDragEvent.prototype"></a>[module react-dom.SyntheticDragEvent.prototype](#apidoc.module.react-dom.SyntheticDragEvent.prototype)

#### <a name="apidoc.element.react-dom.SyntheticDragEvent.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticDragEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticDragEvent.prototype.constructor)
- description and source-code
```javascript
function SyntheticDragEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticMouseEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.SyntheticEvent"></a>[module react-dom.SyntheticEvent](#apidoc.module.react-dom.SyntheticEvent)

#### <a name="apidoc.element.react-dom.SyntheticEvent.SyntheticEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticEvent {{signature}}](#apidoc.element.react-dom.SyntheticEvent.SyntheticEvent)
- description and source-code
```javascript
n/a
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticEvent.augmentClass"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticEvent.augmentClass)
- description and source-code
```javascript
augmentClass = function (Class, Interface) {
  var Super = this;

  var E = function () {};
  E.prototype = Super.prototype;
  var prototype = new E();

  _assign(prototype, Class.prototype);
  Class.prototype = prototype;
  Class.prototype.constructor = Class;

  Class.Interface = _assign({}, Super.Interface, Interface);
  Class.augmentClass = Super.augmentClass;

  PooledClass.addPoolingTo(Class, PooledClass.fourArgumentPooler);
}
```
- example usage
```shell
...
 * @param {object} nativeEvent Native event.
 * @extends {SyntheticEvent}
 */
function ResponderSyntheticEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}

SyntheticEvent.augmentClass(ResponderSyntheticEvent, ResponderEventInterface);

module.exports = ResponderSyntheticEvent;
...
```

#### <a name="apidoc.element.react-dom.SyntheticEvent.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticEvent.getPooled)
- description and source-code
```javascript
getPooled = function (a1, a2, a3, a4) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2, a3, a4);
    return instance;
  } else {
    return new Klass(a1, a2, a3, a4);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.SyntheticEvent.release"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticEvent.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.SyntheticEvent.prototype"></a>[module react-dom.SyntheticEvent.prototype](#apidoc.module.react-dom.SyntheticEvent.prototype)

#### <a name="apidoc.element.react-dom.SyntheticEvent.prototype.destructor"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticEvent.prototype.</span>destructor ()](#apidoc.element.react-dom.SyntheticEvent.prototype.destructor)
- description and source-code
```javascript
destructor = function () {
  var Interface = this.constructor.Interface;
  for (var propName in Interface) {
    if (process.env.NODE_ENV !== 'production') {
      Object.defineProperty(this, propName, getPooledWarningPropertyDefinition(propName, Interface[propName]));
    } else {
      this[propName] = null;
    }
  }
  for (var i = 0; i < shouldBeReleasedProperties.length; i++) {
    this[shouldBeReleasedProperties[i]] = null;
  }
  if (process.env.NODE_ENV !== 'production') {
    Object.defineProperty(this, 'nativeEvent', getPooledWarningPropertyDefinition('nativeEvent', null));
    Object.defineProperty(this, 'preventDefault', getPooledWarningPropertyDefinition('preventDefault', emptyFunction));
    Object.defineProperty(this, 'stopPropagation', getPooledWarningPropertyDefinition('stopPropagation', emptyFunction));
  }
}
```
- example usage
```shell
...
    return new Klass(a1, a2, a3, a4);
  }
};

var standardReleaser = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
};

var DEFAULT_POOL_SIZE = 10;
var DEFAULT_POOLER = oneArgumentPooler;
...
```

#### <a name="apidoc.element.react-dom.SyntheticEvent.prototype.isPersistent"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticEvent.prototype.</span>isPersistent ()](#apidoc.element.react-dom.SyntheticEvent.prototype.isPersistent)
- description and source-code
```javascript
isPersistent = function () {
  return arg;
}
```
- example usage
```shell
...
 * @param {boolean} simulated If the event is simulated (changes exn behavior)
 * @private
 */
var executeDispatchesAndRelease = function (event, simulated) {
  if (event) {
    EventPluginUtils.executeDispatchesInOrder(event, simulated);

    if (!event.isPersistent()) {
      event.constructor.release(event);
    }
  }
};
var executeDispatchesAndReleaseSimulated = function (e) {
  return executeDispatchesAndRelease(e, true);
};
...
```

#### <a name="apidoc.element.react-dom.SyntheticEvent.prototype.persist"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticEvent.prototype.</span>persist ()](#apidoc.element.react-dom.SyntheticEvent.prototype.persist)
- description and source-code
```javascript
persist = function () {
  this.isPersistent = emptyFunction.thatReturnsTrue;
}
```
- example usage
```shell
...
fakeNativeEvent.type = eventType.toLowerCase();

// We don't use SyntheticEvent.getPooled in order to not have to worry about
// properly destroying any properties assigned from 'eventData' upon release
var event = new SyntheticEvent(dispatchConfig, ReactDOMComponentTree.getInstanceFromNode(node), fakeNativeEvent, node);
// Since we aren't using pooling, always persist the event. This will make
// sure it's marked and won't warn when setting additional properties.
event.persist();
_assign(event, eventData);

if (dispatchConfig.phasedRegistrationNames) {
  EventPropagators.accumulateTwoPhaseDispatches(event);
} else {
  EventPropagators.accumulateDirectDispatches(event);
}
...
```

#### <a name="apidoc.element.react-dom.SyntheticEvent.prototype.preventDefault"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticEvent.prototype.</span>preventDefault ()](#apidoc.element.react-dom.SyntheticEvent.prototype.preventDefault)
- description and source-code
```javascript
preventDefault = function () {
  this.defaultPrevented = true;
  var event = this.nativeEvent;
  if (!event) {
    return;
  }

  if (event.preventDefault) {
    event.preventDefault();
  } else if (typeof event.returnValue !== 'unknown') {
    // eslint-disable-line valid-typeof
    event.returnValue = false;
  }
  this.isDefaultPrevented = emptyFunction.thatReturnsTrue;
}
```
- example usage
```shell
...
  this.defaultPrevented = true;
  var event = this.nativeEvent;
  if (!event) {
    return;
  }

  if (event.preventDefault) {
    event.preventDefault();
  } else if (typeof event.returnValue !== 'unknown') {
    // eslint-disable-line valid-typeof
    event.returnValue = false;
  }
  this.isDefaultPrevented = emptyFunction.thatReturnsTrue;
},
...
```

#### <a name="apidoc.element.react-dom.SyntheticEvent.prototype.stopPropagation"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticEvent.prototype.</span>stopPropagation ()](#apidoc.element.react-dom.SyntheticEvent.prototype.stopPropagation)
- description and source-code
```javascript
stopPropagation = function () {
  var event = this.nativeEvent;
  if (!event) {
    return;
  }

  if (event.stopPropagation) {
    event.stopPropagation();
  } else if (typeof event.cancelBubble !== 'unknown') {
    // eslint-disable-line valid-typeof
    // The ChangeEventPlugin registers a "propertychange" event for
    // IE. This event does not support bubbling or cancelling, and
    // any references to cancelBubble throw "Member not found".  A
    // typeof check of "unknown" circumvents this issue (and is also
    // IE specific).
    event.cancelBubble = true;
  }

  this.isPropagationStopped = emptyFunction.thatReturnsTrue;
}
```
- example usage
```shell
...
  stopPropagation: function () {
var event = this.nativeEvent;
if (!event) {
  return;
}

if (event.stopPropagation) {
  event.stopPropagation();
} else if (typeof event.cancelBubble !== 'unknown') {
  // eslint-disable-line valid-typeof
  // The ChangeEventPlugin registers a "propertychange" event for
  // IE. This event does not support bubbling or cancelling, and
  // any references to cancelBubble throw "Member not found".  A
  // typeof check of "unknown" circumvents this issue (and is also
  // IE specific).
...
```



# <a name="apidoc.module.react-dom.SyntheticFocusEvent"></a>[module react-dom.SyntheticFocusEvent](#apidoc.module.react-dom.SyntheticFocusEvent)

#### <a name="apidoc.element.react-dom.SyntheticFocusEvent.SyntheticFocusEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticFocusEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticFocusEvent.SyntheticFocusEvent)
- description and source-code
```javascript
function SyntheticFocusEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticUIEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticFocusEvent.augmentClass"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticFocusEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticFocusEvent.augmentClass)
- description and source-code
```javascript
augmentClass = function (Class, Interface) {
  var Super = this;

  var E = function () {};
  E.prototype = Super.prototype;
  var prototype = new E();

  _assign(prototype, Class.prototype);
  Class.prototype = prototype;
  Class.prototype.constructor = Class;

  Class.Interface = _assign({}, Super.Interface, Interface);
  Class.augmentClass = Super.augmentClass;

  PooledClass.addPoolingTo(Class, PooledClass.fourArgumentPooler);
}
```
- example usage
```shell
...
 * @param {object} nativeEvent Native event.
 * @extends {SyntheticEvent}
 */
function ResponderSyntheticEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}

SyntheticEvent.augmentClass(ResponderSyntheticEvent, ResponderEventInterface);

module.exports = ResponderSyntheticEvent;
...
```

#### <a name="apidoc.element.react-dom.SyntheticFocusEvent.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticFocusEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticFocusEvent.getPooled)
- description and source-code
```javascript
getPooled = function (a1, a2, a3, a4) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2, a3, a4);
    return instance;
  } else {
    return new Klass(a1, a2, a3, a4);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.SyntheticFocusEvent.release"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticFocusEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticFocusEvent.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.SyntheticFocusEvent.prototype"></a>[module react-dom.SyntheticFocusEvent.prototype](#apidoc.module.react-dom.SyntheticFocusEvent.prototype)

#### <a name="apidoc.element.react-dom.SyntheticFocusEvent.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticFocusEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticFocusEvent.prototype.constructor)
- description and source-code
```javascript
function SyntheticFocusEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticUIEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.SyntheticInputEvent"></a>[module react-dom.SyntheticInputEvent](#apidoc.module.react-dom.SyntheticInputEvent)

#### <a name="apidoc.element.react-dom.SyntheticInputEvent.SyntheticInputEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticInputEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticInputEvent.SyntheticInputEvent)
- description and source-code
```javascript
function SyntheticInputEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticInputEvent.augmentClass"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticInputEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticInputEvent.augmentClass)
- description and source-code
```javascript
augmentClass = function (Class, Interface) {
  var Super = this;

  var E = function () {};
  E.prototype = Super.prototype;
  var prototype = new E();

  _assign(prototype, Class.prototype);
  Class.prototype = prototype;
  Class.prototype.constructor = Class;

  Class.Interface = _assign({}, Super.Interface, Interface);
  Class.augmentClass = Super.augmentClass;

  PooledClass.addPoolingTo(Class, PooledClass.fourArgumentPooler);
}
```
- example usage
```shell
...
 * @param {object} nativeEvent Native event.
 * @extends {SyntheticEvent}
 */
function ResponderSyntheticEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}

SyntheticEvent.augmentClass(ResponderSyntheticEvent, ResponderEventInterface);

module.exports = ResponderSyntheticEvent;
...
```

#### <a name="apidoc.element.react-dom.SyntheticInputEvent.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticInputEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticInputEvent.getPooled)
- description and source-code
```javascript
getPooled = function (a1, a2, a3, a4) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2, a3, a4);
    return instance;
  } else {
    return new Klass(a1, a2, a3, a4);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.SyntheticInputEvent.release"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticInputEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticInputEvent.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.SyntheticInputEvent.prototype"></a>[module react-dom.SyntheticInputEvent.prototype](#apidoc.module.react-dom.SyntheticInputEvent.prototype)

#### <a name="apidoc.element.react-dom.SyntheticInputEvent.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticInputEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticInputEvent.prototype.constructor)
- description and source-code
```javascript
function SyntheticInputEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.SyntheticKeyboardEvent"></a>[module react-dom.SyntheticKeyboardEvent](#apidoc.module.react-dom.SyntheticKeyboardEvent)

#### <a name="apidoc.element.react-dom.SyntheticKeyboardEvent.SyntheticKeyboardEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticKeyboardEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticKeyboardEvent.SyntheticKeyboardEvent)
- description and source-code
```javascript
function SyntheticKeyboardEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticUIEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticKeyboardEvent.augmentClass"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticKeyboardEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticKeyboardEvent.augmentClass)
- description and source-code
```javascript
augmentClass = function (Class, Interface) {
  var Super = this;

  var E = function () {};
  E.prototype = Super.prototype;
  var prototype = new E();

  _assign(prototype, Class.prototype);
  Class.prototype = prototype;
  Class.prototype.constructor = Class;

  Class.Interface = _assign({}, Super.Interface, Interface);
  Class.augmentClass = Super.augmentClass;

  PooledClass.addPoolingTo(Class, PooledClass.fourArgumentPooler);
}
```
- example usage
```shell
...
 * @param {object} nativeEvent Native event.
 * @extends {SyntheticEvent}
 */
function ResponderSyntheticEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}

SyntheticEvent.augmentClass(ResponderSyntheticEvent, ResponderEventInterface);

module.exports = ResponderSyntheticEvent;
...
```

#### <a name="apidoc.element.react-dom.SyntheticKeyboardEvent.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticKeyboardEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticKeyboardEvent.getPooled)
- description and source-code
```javascript
getPooled = function (a1, a2, a3, a4) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2, a3, a4);
    return instance;
  } else {
    return new Klass(a1, a2, a3, a4);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.SyntheticKeyboardEvent.release"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticKeyboardEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticKeyboardEvent.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.SyntheticKeyboardEvent.prototype"></a>[module react-dom.SyntheticKeyboardEvent.prototype](#apidoc.module.react-dom.SyntheticKeyboardEvent.prototype)

#### <a name="apidoc.element.react-dom.SyntheticKeyboardEvent.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticKeyboardEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticKeyboardEvent.prototype.constructor)
- description and source-code
```javascript
function SyntheticKeyboardEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticUIEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.SyntheticMouseEvent"></a>[module react-dom.SyntheticMouseEvent](#apidoc.module.react-dom.SyntheticMouseEvent)

#### <a name="apidoc.element.react-dom.SyntheticMouseEvent.SyntheticMouseEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticMouseEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticMouseEvent.SyntheticMouseEvent)
- description and source-code
```javascript
function SyntheticMouseEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticUIEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticMouseEvent.augmentClass"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticMouseEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticMouseEvent.augmentClass)
- description and source-code
```javascript
augmentClass = function (Class, Interface) {
  var Super = this;

  var E = function () {};
  E.prototype = Super.prototype;
  var prototype = new E();

  _assign(prototype, Class.prototype);
  Class.prototype = prototype;
  Class.prototype.constructor = Class;

  Class.Interface = _assign({}, Super.Interface, Interface);
  Class.augmentClass = Super.augmentClass;

  PooledClass.addPoolingTo(Class, PooledClass.fourArgumentPooler);
}
```
- example usage
```shell
...
 * @param {object} nativeEvent Native event.
 * @extends {SyntheticEvent}
 */
function ResponderSyntheticEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}

SyntheticEvent.augmentClass(ResponderSyntheticEvent, ResponderEventInterface);

module.exports = ResponderSyntheticEvent;
...
```

#### <a name="apidoc.element.react-dom.SyntheticMouseEvent.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticMouseEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticMouseEvent.getPooled)
- description and source-code
```javascript
getPooled = function (a1, a2, a3, a4) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2, a3, a4);
    return instance;
  } else {
    return new Klass(a1, a2, a3, a4);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.SyntheticMouseEvent.release"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticMouseEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticMouseEvent.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.SyntheticMouseEvent.prototype"></a>[module react-dom.SyntheticMouseEvent.prototype](#apidoc.module.react-dom.SyntheticMouseEvent.prototype)

#### <a name="apidoc.element.react-dom.SyntheticMouseEvent.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticMouseEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticMouseEvent.prototype.constructor)
- description and source-code
```javascript
function SyntheticMouseEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticUIEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.SyntheticTouchEvent"></a>[module react-dom.SyntheticTouchEvent](#apidoc.module.react-dom.SyntheticTouchEvent)

#### <a name="apidoc.element.react-dom.SyntheticTouchEvent.SyntheticTouchEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticTouchEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticTouchEvent.SyntheticTouchEvent)
- description and source-code
```javascript
function SyntheticTouchEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticUIEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticTouchEvent.augmentClass"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticTouchEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticTouchEvent.augmentClass)
- description and source-code
```javascript
augmentClass = function (Class, Interface) {
  var Super = this;

  var E = function () {};
  E.prototype = Super.prototype;
  var prototype = new E();

  _assign(prototype, Class.prototype);
  Class.prototype = prototype;
  Class.prototype.constructor = Class;

  Class.Interface = _assign({}, Super.Interface, Interface);
  Class.augmentClass = Super.augmentClass;

  PooledClass.addPoolingTo(Class, PooledClass.fourArgumentPooler);
}
```
- example usage
```shell
...
 * @param {object} nativeEvent Native event.
 * @extends {SyntheticEvent}
 */
function ResponderSyntheticEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}

SyntheticEvent.augmentClass(ResponderSyntheticEvent, ResponderEventInterface);

module.exports = ResponderSyntheticEvent;
...
```

#### <a name="apidoc.element.react-dom.SyntheticTouchEvent.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticTouchEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticTouchEvent.getPooled)
- description and source-code
```javascript
getPooled = function (a1, a2, a3, a4) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2, a3, a4);
    return instance;
  } else {
    return new Klass(a1, a2, a3, a4);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.SyntheticTouchEvent.release"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticTouchEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticTouchEvent.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.SyntheticTouchEvent.prototype"></a>[module react-dom.SyntheticTouchEvent.prototype](#apidoc.module.react-dom.SyntheticTouchEvent.prototype)

#### <a name="apidoc.element.react-dom.SyntheticTouchEvent.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticTouchEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticTouchEvent.prototype.constructor)
- description and source-code
```javascript
function SyntheticTouchEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticUIEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.SyntheticTransitionEvent"></a>[module react-dom.SyntheticTransitionEvent](#apidoc.module.react-dom.SyntheticTransitionEvent)

#### <a name="apidoc.element.react-dom.SyntheticTransitionEvent.SyntheticTransitionEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticTransitionEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticTransitionEvent.SyntheticTransitionEvent)
- description and source-code
```javascript
function SyntheticTransitionEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticTransitionEvent.augmentClass"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticTransitionEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticTransitionEvent.augmentClass)
- description and source-code
```javascript
augmentClass = function (Class, Interface) {
  var Super = this;

  var E = function () {};
  E.prototype = Super.prototype;
  var prototype = new E();

  _assign(prototype, Class.prototype);
  Class.prototype = prototype;
  Class.prototype.constructor = Class;

  Class.Interface = _assign({}, Super.Interface, Interface);
  Class.augmentClass = Super.augmentClass;

  PooledClass.addPoolingTo(Class, PooledClass.fourArgumentPooler);
}
```
- example usage
```shell
...
 * @param {object} nativeEvent Native event.
 * @extends {SyntheticEvent}
 */
function ResponderSyntheticEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}

SyntheticEvent.augmentClass(ResponderSyntheticEvent, ResponderEventInterface);

module.exports = ResponderSyntheticEvent;
...
```

#### <a name="apidoc.element.react-dom.SyntheticTransitionEvent.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticTransitionEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticTransitionEvent.getPooled)
- description and source-code
```javascript
getPooled = function (a1, a2, a3, a4) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2, a3, a4);
    return instance;
  } else {
    return new Klass(a1, a2, a3, a4);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.SyntheticTransitionEvent.release"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticTransitionEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticTransitionEvent.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.SyntheticTransitionEvent.prototype"></a>[module react-dom.SyntheticTransitionEvent.prototype](#apidoc.module.react-dom.SyntheticTransitionEvent.prototype)

#### <a name="apidoc.element.react-dom.SyntheticTransitionEvent.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticTransitionEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticTransitionEvent.prototype.constructor)
- description and source-code
```javascript
function SyntheticTransitionEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.SyntheticUIEvent"></a>[module react-dom.SyntheticUIEvent](#apidoc.module.react-dom.SyntheticUIEvent)

#### <a name="apidoc.element.react-dom.SyntheticUIEvent.SyntheticUIEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticUIEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticUIEvent.SyntheticUIEvent)
- description and source-code
```javascript
function SyntheticUIEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticUIEvent.augmentClass"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticUIEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticUIEvent.augmentClass)
- description and source-code
```javascript
augmentClass = function (Class, Interface) {
  var Super = this;

  var E = function () {};
  E.prototype = Super.prototype;
  var prototype = new E();

  _assign(prototype, Class.prototype);
  Class.prototype = prototype;
  Class.prototype.constructor = Class;

  Class.Interface = _assign({}, Super.Interface, Interface);
  Class.augmentClass = Super.augmentClass;

  PooledClass.addPoolingTo(Class, PooledClass.fourArgumentPooler);
}
```
- example usage
```shell
...
 * @param {object} nativeEvent Native event.
 * @extends {SyntheticEvent}
 */
function ResponderSyntheticEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}

SyntheticEvent.augmentClass(ResponderSyntheticEvent, ResponderEventInterface);

module.exports = ResponderSyntheticEvent;
...
```

#### <a name="apidoc.element.react-dom.SyntheticUIEvent.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticUIEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticUIEvent.getPooled)
- description and source-code
```javascript
getPooled = function (a1, a2, a3, a4) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2, a3, a4);
    return instance;
  } else {
    return new Klass(a1, a2, a3, a4);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.SyntheticUIEvent.release"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticUIEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticUIEvent.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.SyntheticUIEvent.prototype"></a>[module react-dom.SyntheticUIEvent.prototype](#apidoc.module.react-dom.SyntheticUIEvent.prototype)

#### <a name="apidoc.element.react-dom.SyntheticUIEvent.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticUIEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticUIEvent.prototype.constructor)
- description and source-code
```javascript
function SyntheticUIEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.SyntheticWheelEvent"></a>[module react-dom.SyntheticWheelEvent](#apidoc.module.react-dom.SyntheticWheelEvent)

#### <a name="apidoc.element.react-dom.SyntheticWheelEvent.SyntheticWheelEvent"></a>[function <span class="apidocSignatureSpan">react-dom.</span>SyntheticWheelEvent (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticWheelEvent.SyntheticWheelEvent)
- description and source-code
```javascript
function SyntheticWheelEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticMouseEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.SyntheticWheelEvent.augmentClass"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticWheelEvent.</span>augmentClass (Class, Interface)](#apidoc.element.react-dom.SyntheticWheelEvent.augmentClass)
- description and source-code
```javascript
augmentClass = function (Class, Interface) {
  var Super = this;

  var E = function () {};
  E.prototype = Super.prototype;
  var prototype = new E();

  _assign(prototype, Class.prototype);
  Class.prototype = prototype;
  Class.prototype.constructor = Class;

  Class.Interface = _assign({}, Super.Interface, Interface);
  Class.augmentClass = Super.augmentClass;

  PooledClass.addPoolingTo(Class, PooledClass.fourArgumentPooler);
}
```
- example usage
```shell
...
 * @param {object} nativeEvent Native event.
 * @extends {SyntheticEvent}
 */
function ResponderSyntheticEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}

SyntheticEvent.augmentClass(ResponderSyntheticEvent, ResponderEventInterface);

module.exports = ResponderSyntheticEvent;
...
```

#### <a name="apidoc.element.react-dom.SyntheticWheelEvent.getPooled"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticWheelEvent.</span>getPooled (a1, a2, a3, a4)](#apidoc.element.react-dom.SyntheticWheelEvent.getPooled)
- description and source-code
```javascript
getPooled = function (a1, a2, a3, a4) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2, a3, a4);
    return instance;
  } else {
    return new Klass(a1, a2, a3, a4);
  }
}
```
- example usage
```shell
...
  return null;
}

if (useFallbackCompositionData) {
  // The current composition is stored statically and must not be
  // overwritten while composition continues.
  if (!currentComposition && eventType === eventTypes.compositionStart) {
    currentComposition = FallbackCompositionState.getPooled(nativeEventTarget);
  } else if (eventType === eventTypes.compositionEnd) {
    if (currentComposition) {
      fallbackData = currentComposition.getData();
    }
  }
}
...
```

#### <a name="apidoc.element.react-dom.SyntheticWheelEvent.release"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticWheelEvent.</span>release (instance)](#apidoc.element.react-dom.SyntheticWheelEvent.release)
- description and source-code
```javascript
release = function (instance) {
  var Klass = this;
  !(instance instanceof Klass) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Trying to release an instance into a
pool of a different type.') : _prodInvariant('25') : void 0;
  instance.destructor();
  if (Klass.instancePool.length < Klass.poolSize) {
    Klass.instancePool.push(instance);
  }
}
```
- example usage
```shell
...
// If we are currently composing (IME) and using a fallback to do so,
// try to extract the composed characters from the fallback object.
// If composition event is available, we extract a string only at
// compositionevent, otherwise extract it at fallback events.
if (currentComposition) {
  if (topLevelType === 'topCompositionEnd' || !canUseCompositionEvent && isFallbackCompositionEnd(topLevelType, nativeEvent)) {
    var chars = currentComposition.getData();
    FallbackCompositionState.release(currentComposition);
    currentComposition = null;
    return chars;
  }
  return null;
}

switch (topLevelType) {
...
```



# <a name="apidoc.module.react-dom.SyntheticWheelEvent.prototype"></a>[module react-dom.SyntheticWheelEvent.prototype](#apidoc.module.react-dom.SyntheticWheelEvent.prototype)

#### <a name="apidoc.element.react-dom.SyntheticWheelEvent.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react-dom.SyntheticWheelEvent.prototype.</span>constructor (dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.SyntheticWheelEvent.prototype.constructor)
- description and source-code
```javascript
function SyntheticWheelEvent(dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget) {
  return SyntheticMouseEvent.call(this, dispatchConfig, dispatchMarker, nativeEvent, nativeEventTarget);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.TapEventPlugin"></a>[module react-dom.TapEventPlugin](#apidoc.module.react-dom.TapEventPlugin)

#### <a name="apidoc.element.react-dom.TapEventPlugin.extractEvents"></a>[function <span class="apidocSignatureSpan">react-dom.TapEventPlugin.</span>extractEvents (topLevelType, targetInst, nativeEvent, nativeEventTarget)](#apidoc.element.react-dom.TapEventPlugin.extractEvents)
- description and source-code
```javascript
extractEvents = function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  if (!isStartish(topLevelType) && !isEndish(topLevelType)) {
    return null;
  }
  // on ios, there is a delay after touch event and synthetic
  // mouse events, so that user can perform double tap
  // solution: ignore mouse events following touchevent within small timeframe
  if (touchEvents.indexOf(topLevelType) !== -1) {
    usedTouch = true;
    usedTouchTime = Date.now();
  } else {
    if (usedTouch && Date.now() - usedTouchTime < TOUCH_DELAY) {
      return null;
    }
  }
  var event = null;
  var distance = getDistance(startCoords, nativeEvent);
  if (isEndish(topLevelType) && distance < tapMoveThreshold) {
    event = SyntheticUIEvent.getPooled(eventTypes.touchTap, targetInst, nativeEvent, nativeEventTarget);
  }
  if (isStartish(topLevelType)) {
    startCoords.x = getAxisCoordOfEvent(Axis.x, nativeEvent);
    startCoords.y = getAxisCoordOfEvent(Axis.y, nativeEvent);
  } else if (isEndish(topLevelType)) {
    startCoords.x = 0;
    startCoords.y = 0;
  }
  EventPropagators.accumulateTwoPhaseDispatches(event);
  return event;
}
```
- example usage
```shell
...
extractEvents: function (topLevelType, targetInst, nativeEvent, nativeEventTarget) {
  var events;
  var plugins = EventPluginRegistry.plugins;
  for (var i = 0; i < plugins.length; i++) {
    // Not every plugin in the ordering may be loaded at runtime.
    var possiblePlugin = plugins[i];
    if (possiblePlugin) {
      var extractedEvents = possiblePlugin.extractEvents(topLevelType, targetInst, nativeEvent, nativeEventTarget);
      if (extractedEvents) {
        events = accumulateInto(events, extractedEvents);
      }
    }
  }
  return events;
},
...
```



# <a name="apidoc.module.react-dom.TouchHistoryMath"></a>[module react-dom.TouchHistoryMath](#apidoc.module.react-dom.TouchHistoryMath)

#### <a name="apidoc.element.react-dom.TouchHistoryMath.centroidDimension"></a>[function <span class="apidocSignatureSpan">react-dom.TouchHistoryMath.</span>centroidDimension (touchHistory, touchesChangedAfter, isXAxis, ofCurrent)](#apidoc.element.react-dom.TouchHistoryMath.centroidDimension)
- description and source-code
```javascript
centroidDimension = function (touchHistory, touchesChangedAfter, isXAxis, ofCurrent) {
  var touchBank = touchHistory.touchBank;
  var total = 0;
  var count = 0;

  var oneTouchData = touchHistory.numberActiveTouches === 1 ? touchHistory.touchBank[touchHistory.indexOfSingleActiveTouch] : null
;

  if (oneTouchData !== null) {
    if (oneTouchData.touchActive && oneTouchData.currentTimeStamp > touchesChangedAfter) {
      total += ofCurrent && isXAxis ? oneTouchData.currentPageX : ofCurrent && !isXAxis ? oneTouchData.currentPageY : !ofCurrent
 && isXAxis ? oneTouchData.previousPageX : oneTouchData.previousPageY;
      count = 1;
    }
  } else {
    for (var i = 0; i < touchBank.length; i++) {
      var touchTrack = touchBank[i];
      if (touchTrack !== null && touchTrack !== undefined && touchTrack.touchActive && touchTrack.currentTimeStamp >= touchesChangedAfter
) {
        var toAdd; // Yuck, program temporarily in invalid state.
        if (ofCurrent && isXAxis) {
          toAdd = touchTrack.currentPageX;
        } else if (ofCurrent && !isXAxis) {
          toAdd = touchTrack.currentPageY;
        } else if (!ofCurrent && isXAxis) {
          toAdd = touchTrack.previousPageX;
        } else {
          toAdd = touchTrack.previousPageY;
        }
        total += toAdd;
        count++;
      }
    }
  }
  return count > 0 ? total / count : TouchHistoryMath.noCentroid;
}
```
- example usage
```shell
...
      }
    }
  }
  return count > 0 ? total / count : TouchHistoryMath.noCentroid;
},

currentCentroidXOfTouchesChangedAfter: function (touchHistory, touchesChangedAfter) {
  return TouchHistoryMath.centroidDimension(touchHistory, touchesChangedAfter, true, // isXAxis
  true // ofCurrent
  );
},

currentCentroidYOfTouchesChangedAfter: function (touchHistory, touchesChangedAfter) {
  return TouchHistoryMath.centroidDimension(touchHistory, touchesChangedAfter, false, // isXAxis
  true // ofCurrent
...
```

#### <a name="apidoc.element.react-dom.TouchHistoryMath.currentCentroidX"></a>[function <span class="apidocSignatureSpan">react-dom.TouchHistoryMath.</span>currentCentroidX (touchHistory)](#apidoc.element.react-dom.TouchHistoryMath.currentCentroidX)
- description and source-code
```javascript
currentCentroidX = function (touchHistory) {
  return TouchHistoryMath.centroidDimension(touchHistory, 0, // touchesChangedAfter
  true, // isXAxis
  true // ofCurrent
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.TouchHistoryMath.currentCentroidXOfTouchesChangedAfter"></a>[function <span class="apidocSignatureSpan">react-dom.TouchHistoryMath.</span>currentCentroidXOfTouchesChangedAfter (touchHistory, touchesChangedAfter)](#apidoc.element.react-dom.TouchHistoryMath.currentCentroidXOfTouchesChangedAfter)
- description and source-code
```javascript
currentCentroidXOfTouchesChangedAfter = function (touchHistory, touchesChangedAfter) {
  return TouchHistoryMath.centroidDimension(touchHistory, touchesChangedAfter, true, // isXAxis
  true // ofCurrent
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.TouchHistoryMath.currentCentroidY"></a>[function <span class="apidocSignatureSpan">react-dom.TouchHistoryMath.</span>currentCentroidY (touchHistory)](#apidoc.element.react-dom.TouchHistoryMath.currentCentroidY)
- description and source-code
```javascript
currentCentroidY = function (touchHistory) {
  return TouchHistoryMath.centroidDimension(touchHistory, 0, // touchesChangedAfter
  false, // isXAxis
  true // ofCurrent
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.TouchHistoryMath.currentCentroidYOfTouchesChangedAfter"></a>[function <span class="apidocSignatureSpan">react-dom.TouchHistoryMath.</span>currentCentroidYOfTouchesChangedAfter (touchHistory, touchesChangedAfter)](#apidoc.element.react-dom.TouchHistoryMath.currentCentroidYOfTouchesChangedAfter)
- description and source-code
```javascript
currentCentroidYOfTouchesChangedAfter = function (touchHistory, touchesChangedAfter) {
  return TouchHistoryMath.centroidDimension(touchHistory, touchesChangedAfter, false, // isXAxis
  true // ofCurrent
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.TouchHistoryMath.previousCentroidXOfTouchesChangedAfter"></a>[function <span class="apidocSignatureSpan">react-dom.TouchHistoryMath.</span>previousCentroidXOfTouchesChangedAfter (touchHistory, touchesChangedAfter)](#apidoc.element.react-dom.TouchHistoryMath.previousCentroidXOfTouchesChangedAfter)
- description and source-code
```javascript
previousCentroidXOfTouchesChangedAfter = function (touchHistory, touchesChangedAfter) {
  return TouchHistoryMath.centroidDimension(touchHistory, touchesChangedAfter, true, // isXAxis
  false // ofCurrent
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.TouchHistoryMath.previousCentroidYOfTouchesChangedAfter"></a>[function <span class="apidocSignatureSpan">react-dom.TouchHistoryMath.</span>previousCentroidYOfTouchesChangedAfter (touchHistory, touchesChangedAfter)](#apidoc.element.react-dom.TouchHistoryMath.previousCentroidYOfTouchesChangedAfter)
- description and source-code
```javascript
previousCentroidYOfTouchesChangedAfter = function (touchHistory, touchesChangedAfter) {
  return TouchHistoryMath.centroidDimension(touchHistory, touchesChangedAfter, false, // isXAxis
  false // ofCurrent
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.Transaction"></a>[module react-dom.Transaction](#apidoc.module.react-dom.Transaction)

#### <a name="apidoc.element.react-dom.Transaction.closeAll"></a>[function <span class="apidocSignatureSpan">react-dom.Transaction.</span>closeAll (startIndex)](#apidoc.element.react-dom.Transaction.closeAll)
- description and source-code
```javascript
closeAll = function (startIndex) {
  !this.isInTransaction() ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Transaction.closeAll(): Cannot close transaction
 when none are open.') : _prodInvariant('28') : void 0;
  var transactionWrappers = this.transactionWrappers;
  for (var i = startIndex; i < transactionWrappers.length; i++) {
    var wrapper = transactionWrappers[i];
    var initData = this.wrapperInitData[i];
    var errorThrown;
    try {
      // Catching errors makes debugging more difficult, so we start with
      // errorThrown set to true before setting it to false after calling
      // close -- if it's still set to true in the finally block, it means
      // wrapper.close threw.
      errorThrown = true;
      if (initData !== OBSERVED_ERROR && wrapper.close) {
        wrapper.close.call(this, initData);
      }
      errorThrown = false;
    } finally {
      if (errorThrown) {
        // The closer for wrapper i threw an error; close the remaining
        // wrappers but silence any exceptions from them to ensure that the
        // first error is the one to bubble up.
        try {
          this.closeAll(i + 1);
        } catch (e) {}
      }
    }
  }
  this.wrapperInitData.length = 0;
}
```
- example usage
```shell
...
  errorThrown = false;
} finally {
  try {
    if (errorThrown) {
      // If 'method' throws, prefer to show that stack trace over any thrown
      // by invoking 'closeAll'.
      try {
        this.closeAll(0);
      } catch (err) {}
    } else {
      // Since 'method' didn't throw, we don't want to silence the exception
      // here.
      this.closeAll(0);
    }
  } finally {
...
```

#### <a name="apidoc.element.react-dom.Transaction.initializeAll"></a>[function <span class="apidocSignatureSpan">react-dom.Transaction.</span>initializeAll (startIndex)](#apidoc.element.react-dom.Transaction.initializeAll)
- description and source-code
```javascript
initializeAll = function (startIndex) {
  var transactionWrappers = this.transactionWrappers;
  for (var i = startIndex; i < transactionWrappers.length; i++) {
    var wrapper = transactionWrappers[i];
    try {
      // Catching errors makes debugging more difficult, so we start with the
      // OBSERVED_ERROR state before overwriting it with the real return value
      // of initialize -- if it's still set to OBSERVED_ERROR in the finally
      // block, it means wrapper.initialize threw.
      this.wrapperInitData[i] = OBSERVED_ERROR;
      this.wrapperInitData[i] = wrapper.initialize ? wrapper.initialize.call(this) : null;
    } finally {
      if (this.wrapperInitData[i] === OBSERVED_ERROR) {
        // The initializer for wrapper i threw an error; initialize the
        // remaining wrappers but silence any exceptions from them to ensure
        // that the first error is the one to bubble up.
        try {
          this.initializeAll(i + 1);
        } catch (err) {}
      }
    }
  }
}
```
- example usage
```shell
...
try {
  this._isInTransaction = true;
  // Catching errors makes debugging more difficult, so we start with
  // errorThrown set to true before setting it to false after calling
  // close -- if it's still set to true in the finally block, it means
  // one of these calls threw.
  errorThrown = true;
  this.initializeAll(0);
  ret = method.call(scope, a, b, c, d, e, f);
  errorThrown = false;
} finally {
  try {
    if (errorThrown) {
      // If 'method' throws, prefer to show that stack trace over any thrown
      // by invoking 'closeAll'.
...
```

#### <a name="apidoc.element.react-dom.Transaction.isInTransaction"></a>[function <span class="apidocSignatureSpan">react-dom.Transaction.</span>isInTransaction ()](#apidoc.element.react-dom.Transaction.isInTransaction)
- description and source-code
```javascript
isInTransaction = function () {
  return !!this._isInTransaction;
}
```
- example usage
```shell
...
 * @param {ReactClass} publicInstance The instance to use as 'this' context.
 * @param {?function} callback Called after state is updated.
 * @internal
 */


ReactServerUpdateQueue.prototype.enqueueCallback = function enqueueCallback(publicInstance, callback, callerName) {
  if (this.transaction.isInTransaction()) {
    ReactUpdateQueue.enqueueCallback(publicInstance, callback, callerName);
  }
};

/**
 * Forces an update. This should only be invoked when it is known with
 * certainty that we are **not** in a DOM transaction.
...
```

#### <a name="apidoc.element.react-dom.Transaction.perform"></a>[function <span class="apidocSignatureSpan">react-dom.Transaction.</span>perform (method, scope, a, b, c, d, e, f)](#apidoc.element.react-dom.Transaction.perform)
- description and source-code
```javascript
perform = function (method, scope, a, b, c, d, e, f) {
  !!this.isInTransaction() ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Transaction.perform(...): Cannot initialize
 a transaction when there is already an outstanding transaction.') : _prodInvariant('27') : void 0;
  var errorThrown;
  var ret;
  try {
    this._isInTransaction = true;
    // Catching errors makes debugging more difficult, so we start with
    // errorThrown set to true before setting it to false after calling
    // close -- if it's still set to true in the finally block, it means
    // one of these calls threw.
    errorThrown = true;
    this.initializeAll(0);
    ret = method.call(scope, a, b, c, d, e, f);
    errorThrown = false;
  } finally {
    try {
      if (errorThrown) {
        // If 'method' throws, prefer to show that stack trace over any thrown
        // by invoking 'closeAll'.
        try {
          this.closeAll(0);
        } catch (err) {}
      } else {
        // Since 'method' didn't throw, we don't want to silence the exception
        // here.
        this.closeAll(0);
      }
    } finally {
      this._isInTransaction = false;
    }
  }
  return ret;
}
```
- example usage
```shell
...

    ReactDefaultBatchingStrategy.isBatchingUpdates = true;

    // The code is written this way to avoid extra allocations
    if (alreadyBatchingUpdates) {
      return callback(a, b, c, d, e);
    } else {
      return transaction.perform(callback, null, a, b, c, d, e);
    }
  }
};

module.exports = ReactDefaultBatchingStrategy;
...
```

#### <a name="apidoc.element.react-dom.Transaction.reinitializeTransaction"></a>[function <span class="apidocSignatureSpan">react-dom.Transaction.</span>reinitializeTransaction ()](#apidoc.element.react-dom.Transaction.reinitializeTransaction)
- description and source-code
```javascript
reinitializeTransaction = function () {
  this.transactionWrappers = this.getTransactionWrappers();
  if (this.wrapperInitData) {
    this.wrapperInitData.length = 0;
  } else {
    this.wrapperInitData = [];
  }
  this._isInTransaction = false;
}
```
- example usage
```shell
...
  initialize: emptyFunction,
  close: ReactUpdates.flushBatchedUpdates.bind(ReactUpdates)
};

var TRANSACTION_WRAPPERS = [FLUSH_BATCHED_UPDATES, RESET_BATCHED_UPDATES];

function ReactDefaultBatchingStrategyTransaction() {
  this.reinitializeTransaction();
}

_assign(ReactDefaultBatchingStrategyTransaction.prototype, Transaction, {
  getTransactionWrappers: function () {
    return TRANSACTION_WRAPPERS;
  }
});
...
```



# <a name="apidoc.module.react-dom.ViewportMetrics"></a>[module react-dom.ViewportMetrics](#apidoc.module.react-dom.ViewportMetrics)

#### <a name="apidoc.element.react-dom.ViewportMetrics.refreshScrollValues"></a>[function <span class="apidocSignatureSpan">react-dom.ViewportMetrics.</span>refreshScrollValues (scrollPosition)](#apidoc.element.react-dom.ViewportMetrics.refreshScrollValues)
- description and source-code
```javascript
refreshScrollValues = function (scrollPosition) {
  ViewportMetrics.currentScrollLeft = scrollPosition.x;
  ViewportMetrics.currentScrollTop = scrollPosition.y;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-dom.validateDOMNesting"></a>[module react-dom.validateDOMNesting](#apidoc.module.react-dom.validateDOMNesting)

#### <a name="apidoc.element.react-dom.validateDOMNesting.validateDOMNesting"></a>[function <span class="apidocSignatureSpan">react-dom.</span>validateDOMNesting (childTag, childText, childInstance, ancestorInfo)](#apidoc.element.react-dom.validateDOMNesting.validateDOMNesting)
- description and source-code
```javascript
validateDOMNesting = function (childTag, childText, childInstance, ancestorInfo) {
  ancestorInfo = ancestorInfo || emptyAncestorInfo;
  var parentInfo = ancestorInfo.current;
  var parentTag = parentInfo && parentInfo.tag;

  if (childText != null) {
    process.env.NODE_ENV !== 'production' ? warning(childTag == null, 'validateDOMNesting: when childText is passed, childTag should
 be null') : void 0;
    childTag = '#text';
  }

  var invalidParent = isTagValidWithParent(childTag, parentTag) ? null : parentInfo;
  var invalidAncestor = invalidParent ? null : findInvalidAncestorForTag(childTag, ancestorInfo);
  var problematic = invalidParent || invalidAncestor;

  if (problematic) {
    var ancestorTag = problematic.tag;
    var ancestorInstance = problematic.instance;

    var childOwner = childInstance && childInstance._currentElement._owner;
    var ancestorOwner = ancestorInstance && ancestorInstance._currentElement._owner;

    var childOwners = findOwnerStack(childOwner);
    var ancestorOwners = findOwnerStack(ancestorOwner);

    var minStackLen = Math.min(childOwners.length, ancestorOwners.length);
    var i;

    var deepestCommon = -1;
    for (i = 0; i < minStackLen; i++) {
      if (childOwners[i] === ancestorOwners[i]) {
        deepestCommon = i;
      } else {
        break;
      }
    }

    var UNKNOWN = '(unknown)';
    var childOwnerNames = childOwners.slice(deepestCommon + 1).map(function (inst) {
      return inst.getName() || UNKNOWN;
    });
    var ancestorOwnerNames = ancestorOwners.slice(deepestCommon + 1).map(function (inst) {
      return inst.getName() || UNKNOWN;
    });
    var ownerInfo = [].concat(
    // If the parent and child instances have a common owner ancestor, start
    // with that -- otherwise we just start with the parent's owners.
    deepestCommon !== -1 ? childOwners[deepestCommon].getName() || UNKNOWN : [], ancestorOwnerNames, ancestorTag,
    // If we're warning about an invalid (non-parent) ancestry, add '...'
    invalidAncestor ? ['...'] : [], childOwnerNames, childTag).join(' > ');

    var warnKey = !!invalidParent + '|' + childTag + '|' + ancestorTag + '|' + ownerInfo;
    if (didWarn[warnKey]) {
      return;
    }
    didWarn[warnKey] = true;

    var tagDisplayName = childTag;
    var whitespaceInfo = '';
    if (childTag === '#text') {
      if (/\S/.test(childText)) {
        tagDisplayName = 'Text nodes';
      } else {
        tagDisplayName = 'Whitespace text nodes';
        whitespaceInfo = ' Make sure you don\'t have any extra whitespace between tags on ' + 'each line of your source code.';
      }
    } else {
      tagDisplayName = '<' + childTag + '>';
    }

    if (invalidParent) {
      var info = '';
      if (ancestorTag === 'table' && childTag === 'tr') {
        info += ' Add a <tbody> to your code to match the DOM tree generated by ' + 'the browser.';
      }
      process.env.NODE_ENV !== 'production' ? warning(false, 'validateDOMNesting(...): %s cannot appear as a child of <%s>.%s ' + '
See %s.%s', tagDisplayName, ancestorTag, whitespaceInfo, ownerInfo, info) : void 0;
    } else {
      process.env.NODE_ENV !== 'production' ? warning(false, 'validateDOMNesting(...): %s cannot appear as a descendant of ' + '<%
s>. See %s.', tagDisplayName, ancestorTag, ownerInfo) : void 0;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.validateDOMNesting.isTagValidInContext"></a>[function <span class="apidocSignatureSpan">react-dom.validateDOMNesting.</span>isTagValidInContext (tag, ancestorInfo)](#apidoc.element.react-dom.validateDOMNesting.isTagValidInContext)
- description and source-code
```javascript
isTagValidInContext = function (tag, ancestorInfo) {
  ancestorInfo = ancestorInfo || emptyAncestorInfo;
  var parentInfo = ancestorInfo.current;
  var parentTag = parentInfo && parentInfo.tag;
  return isTagValidWithParent(tag, parentTag) && !findInvalidAncestorForTag(tag, ancestorInfo);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-dom.validateDOMNesting.updatedAncestorInfo"></a>[function <span class="apidocSignatureSpan">react-dom.validateDOMNesting.</span>updatedAncestorInfo (oldInfo, tag, instance)](#apidoc.element.react-dom.validateDOMNesting.updatedAncestorInfo)
- description and source-code
```javascript
updatedAncestorInfo = function (oldInfo, tag, instance) {
  var ancestorInfo = _assign({}, oldInfo || emptyAncestorInfo);
  var info = { tag: tag, instance: instance };

  if (inScopeTags.indexOf(tag) !== -1) {
    ancestorInfo.aTagInScope = null;
    ancestorInfo.buttonTagInScope = null;
    ancestorInfo.nobrTagInScope = null;
  }
  if (buttonScopeTags.indexOf(tag) !== -1) {
    ancestorInfo.pTagInButtonScope = null;
  }

  // See rules for 'li', 'dd', 'dt' start tags in
  // https://html.spec.whatwg.org/multipage/syntax.html#parsing-main-inbody
  if (specialTags.indexOf(tag) !== -1 && tag !== 'address' && tag !== 'div' && tag !== 'p') {
    ancestorInfo.listItemTagAutoclosing = null;
    ancestorInfo.dlItemTagAutoclosing = null;
  }

  ancestorInfo.current = info;

  if (tag === 'form') {
    ancestorInfo.formTag = info;
  }
  if (tag === 'a') {
    ancestorInfo.aTagInScope = info;
  }
  if (tag === 'button') {
    ancestorInfo.buttonTagInScope = info;
  }
  if (tag === 'nobr') {
    ancestorInfo.nobrTagInScope = info;
  }
  if (tag === 'p') {
    ancestorInfo.pTagInButtonScope = info;
  }
  if (tag === 'li') {
    ancestorInfo.listItemTagAutoclosing = info;
  }
  if (tag === 'dd' || tag === 'dt') {
    ancestorInfo.dlItemTagAutoclosing = info;
  }

  return ancestorInfo;
}
```
- example usage
```shell
...
    parentInfo = hostContainerInfo._ancestorInfo;
  }
  if (parentInfo) {
    // parentInfo should always be present except for the top-level
    // component when server rendering
    validateDOMNesting(this._tag, null, this, parentInfo);
  }
  this._ancestorInfo = validateDOMNesting.updatedAncestorInfo(parentInfo, this._tag, this);
}

var mountImage;
if (transaction.useCreateElement) {
  var ownerDocument = hostContainerInfo._ownerDocument;
  var el;
  if (namespaceURI === DOMNamespaces.html) {
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
