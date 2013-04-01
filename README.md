OpenFaust Time-as-a-Service platform
=========

For those of us with too much to do and too little time to do it, OpenFaust defines a time-stealing platform. The API is simple, consisting of three calls:

makeBargain() - this call is idempotent, and must be made before any other calls.

stealTime(amount) - amount may be specified as seconds, minutes, hours, days, weeks, months, years, epochs, eras, or eons.

cancelBargain() - this call is supported, but always returns '403 Forbidden'
