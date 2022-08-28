# API para o React 18

1. Children: {map: ƒ, forEach: ƒ, count: ƒ, toArray: ƒ, only: ƒ}
1. Component: ƒ Component(props, context, updater)
1. Fragment: Symbol(react.fragment)
1. Profiler: Symbol(react.profiler)
1. PureComponent: ƒ PureComponent(props, context, updater)
1. StrictMode: Symbol(react.strict_mode)
1. Suspense: Symbol(react.suspense)
1. cloneElement: ƒ cloneElementWithValidation(element, props, children)
1. createContext: ƒ createContext(defaultValue, calculateChangedBits)
1. createElement: ƒ createElementWithValidation(type, props, children)
1. createFactory: ƒ createFactoryWithValidation(type)
1. createRef: ƒ createRef()
1. forwardRef: ƒ forwardRef(render)
1. isValidElement: ƒ isValidElement(object)
1. lazy: ƒ lazy(ctor)
1. memo: ƒ memo(type, compare)
1. useCallback: ƒ useCallback(callback, deps)
1. useContext: ƒ useContext(Context, unstable_observedBits)
1. useDebugValue: ƒ useDebugValue(value, formatterFn)
1. useEffect: ƒ useEffect(create, deps)
1. useImperativeHandle: ƒ useImperativeHandle(ref, create, deps)
1. useLayoutEffect: ƒ useLayoutEffect(create, deps)
1. useMemo: ƒ useMemo(create, deps)
1. useReducer: ƒ useReducer(reducer, initialArg, init)
1. useRef: ƒ useRef(initialValue)
1. useState: ƒ useState(initialState)

# API do ReactDOM 17

1. createPortal: ƒ createPortal$1(children, container)
1. findDOMNode: ƒ findDOMNode(componentOrElement)
1. flushSync: ƒ flushSync(fn, a)
1. hydrate: ƒ hydrate(element, container, callback)
1. render: ƒ render(element, container, callback)
1. unmountComponentAtNode: ƒ unmountComponentAtNode(container)
1. unstable_batchedUpdates: ƒ batchedUpdates$1(fn, a)
1. unstable_createPortal: ƒ unstable_createPortal(children, container)
1. unstable_renderSubtreeIntoContainer: ƒ renderSubtreeIntoContainer(parentComponent, element, containerNode, callback)