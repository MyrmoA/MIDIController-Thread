Arduino does not support "REAL" parallel tasks (aka Threads), but we can make use of this Library to improve our code, and easily schedule tasks with fixed (or variable) time between runs.

This Library helps to maintain organized and to facilitate the use of multiple tasks. We can use Timers Interrupts, and make it really powerfull, running "pseudo-background" tasks under the rug.

For example, I personaly use it for all my projects, and put all sensor aquisition and filtering inside it, leaving the main loop, just for logic and "cool" part.
