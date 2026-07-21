# 🚀 Level 3 – [React Internals & Rendering](rendering-internals.md)

---

# Part A – Rendering Pipeline

## 3.1 Rendering Pipeline

- [x] setState()
- [x] Update Queue
- [x] Scheduler
- [x] Render Phase
- [x] Commit Phase
- [x] Browser Paint
- [x] useEffect
- [x] useLayoutEffect
- [x] Render vs DOM Update
- [x] Rendering Timeline

---

## 3.2 Fiber Architecture

- [x] Why Fiber
- [x] Synchronous vs Interruptible Rendering
- [x] Unit of Work
- [x] Fiber Node
- [x] Fiber Tree
- [x] Parent / Child / Sibling Fibers
- [x] Scheduler vs Fiber
- [x] Time Slicing
- [x] Priority Scheduling

---

## 3.3 Work Loop

- [x] Work Loop
- [x] Processing Fibers
- [x] Pause Rendering
- [x] Resume Rendering
- [x] Interrupt Rendering
- [x] Discard Stale Work
- [x] Reuse Completed Work

---

## 3.4 Alternate Fiber Tree

- [x] Current Fiber Tree
- [x] Work-In-Progress Fiber Tree
- [x] Double Buffering
- [x] Tree Swap
- [x] Commit Phase
- [x] Immutable Current Tree

---

# Part B – Rendering Behaviour

## 3.5 Reconciliation

- [x] Reconciliation
- [x] Diffing Algorithm
- [x] Why O(n)
- [x] React's Two Assumptions
- [x] Tree Comparison
- [x] Component Identity
- [x] Mount
- [x] Update
- [x] Remount
- [x] Keys
- [x] Key vs Props vs Component Type
- [x] State belongs to Component Instance

---

## 3.6 What Causes Re-renders

- [x] State Updates
- [x] Parent Re-render
- [x] Props Changes
- [x] Context Changes
- [x] Force Updates
- [x] Render vs DOM Update
- [x] Component Render vs DOM Commit

---

## 3.7 React.memo

### Fundamentals

- [x] Why React.memo
- [x] React.memo Workflow
- [x] Parent Still Renders
- [x] Child Execution Skipped
- [x] React Elements Still Created
- [x] React.memo Cost

### Deep Dive

- [x] Shallow Comparison
- [x] Reference Equality
- [x] Primitive vs Reference Values
- [x] Object Identity
- [x] Function Identity
- [x] Custom Comparator (areEqual)
- [x] Memoization Cost
- [x] When NOT to use React.memo

---

## 3.8 useMemo

- [x] Why useMemo
- [x] Dependency Array
- [x] Cache Lifecycle
- [x] Expensive Calculations
- [x] Derived Data
- [x] Object Memoization
- [x] Array Memoization
- [x] Common Mistakes

---

## 3.9 useCallback

- [x] Why useCallback
- [x] Function Identity
- [x] Stable References
- [x] Parent → Child Optimization
- [x] Dependency Array
- [x] Stale Closures
- [x] Common Mistakes

---

## 3.10 Rendering Optimization

- [x] Component Splitting
- [x] State Placement
- [x] Composition
- [x] Children as JSX
- [x] List Optimization
- [x] Windowing / Virtualization
- [x] Lazy Components
- [x] Code Splitting
- [x] Dynamic Imports

---

# Part C – Modern React Rendering

## 3.11 Automatic Batching

- [x] Automatic Batching
- [x] React 18 Changes
- [x] flushSync

---

## 3.12 Concurrent Rendering

- [x] Concurrent Rendering
- [x] Interruptible Rendering
- [x] Lanes
- [x] Scheduler Priorities

---

## 3.13 Suspense

- [x] Suspense
- [x] Fallback UI
- [x] React.lazy
- [x] Suspense Boundaries
- [x] Suspense for Data Fetching

---

## 3.14 useTransition

- [x] startTransition
- [x] Transition Updates
- [x] Pending State
- [x] Urgent vs Non-Urgent Updates

---

## 3.15 useDeferredValue

- [x] useDeferredValue
- [x] Deferred Rendering
- [x] Search Optimization
- [x] Expensive Lists

---

# Part D – Performance & Debugging

## 3.16 Performance Debugging

- [ ] React DevTools
- [ ] React Profiler
- [ ] Flame Graph
- [ ] Why Did This Render?
- [ ] Performance Bottlenecks
- [ ] Measuring Re-renders
- [ ] Debugging Slow Components
