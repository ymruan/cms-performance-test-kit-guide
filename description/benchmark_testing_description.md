# Benchmarking

System Benchmark Testing Scenarios
The UCMDB system benchmark testing lasts 8 hours including

*	Data-in: "1 data-in user". Each data-in user performs insert of bulk of 10K CIs 1 time, then update of those 10K CIs 3 times and then delete of 10K CIs.
*	Enrichment: "1 enrichment user". Each enrichment user performs insert-update-delete of 3K CIs, in the interval of each operation is 15 minutes.
*	TQL calculation: "13 TQL users". Each user calculates 10 TQLs in interval of 100 seconds and then saves and deletes TQLs each 30 seconds.
*	View: "6 view users". Each user saves and deletes views each 30 seconds, gets all views each 1 minute.
