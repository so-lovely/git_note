# Asyncio
- asyncio is good for I/O bound tasks.
- asyncio is worked in one thread.
- multiprocess is good for complex CPU computing tasks.
- asyncio is good for low threads computer.


**asyncio**
asyncio is a coorutine.

**await**
await is wait for the executing coorutine.

**await asyncio.run()**
- Make one coorutine to start.
- asyncio.run() converts awaitable objects to tasks automatically.



**await asyncio.gather(awaitable)**
Start awaitable params concurrently.

**await asyncio.sleep**

