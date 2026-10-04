# Structured Reflection - IE3090 RemoteOps (IT24102550)

## AI Tools Used
I used Claude (DeepSeek) as a coding assistant for explaining socket API functions, providing boilerplate code, debugging errors, and suggesting design patterns.

## What AI Did Well
- Generated correct socket programming boilerplate
- Explained complex concepts clearly
- Helped identify and fix warnings

## Where AI Got Things Wrong
- Suggested BUFFER_SIZE for all buffers causing overflow warnings
- Did not account for function prototype ordering

## What I Changed, Added, or Rejected
- Changed: Buffer sizes to BUFFER_SIZE / 2
- Added: (void)arg; to suppress warnings
- Personalised: All values to my registration number

## What I Learned
1. Socket programming (TCP + UDP)
2. Protocol implementation
3. Concurrency with pthreads
4. File transfer with byte counting
5. Debugging compiler warnings
6. Understanding code deeply

The assignment taught me that AI is a powerful tool but requires critical evaluation.
