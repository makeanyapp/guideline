# Semantic Comment

## Critical (Must treat it with care!)
- SAFETY - Use to explain **why** when the implementation *seems* like it can be panic, or causing serious problem, but it is actually safe to do.
- FIXME - This is not an acceptable solution and might cause serious problem in the future, should be fix as soon as possible.

## Insighful (Just a description)
- TODO - What we should do, Things we should do
- SECTION - Explain what a section or a block of code do.
- NOTE - Some **non-critical** information that will make a future implementor grateful.
- CAUTION - Some **critical** information that will make a future implementor grateful.

## Indicate a problem
- BUG - Indicate a bug, should be fix as soon as possible.
- HACK - Indicate a hacky workaround (but correct) which need to be fix with a proper implementation as soon as possible

## Need incremental improvement (Short-term Solution)
- IMPROVEMENT - Things that we should do which might improve readability, performance or correctness (hard to make mistake) of codebase.
- WORKAROUND - Indicate a working solution which might not be the best but a proper solution might take a large rewrite or too much time in order to make an important feature work.
- OPTIMIZE - The performance can be improve by using a correct datastructure or rewrite an algorithm.
- EXPERIMENTAL - This section of code might be remove in the future but it will not impact other functions or modules.
