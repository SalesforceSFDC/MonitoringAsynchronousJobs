# Monitoring Asynchronous Jobs

* Async jobs work silently in the background.
* Apex Flex queue enables you to submit up to 100 jobs for execution.  Any jobs that are submitted for execution are in holding status and are placed in Apex Flex queue.  Up to 100 jobs can be in the holding status.  Jobs are processed first-in first-out—in the order in which they’re submitted. You can look at the current queue order and shuffle the queue, so that you could move an important job to the front, or less important ones to the back.  
* When system resources become available, the system picks up the next job from the top of the Apex Flex queue and moves it to the batch job queue. The system can process up to five queued or active jobs simultaneously for each organization. The status of these moved jobs changes from Holding to Queued. Queued jobs get executed when the system is ready to process new jobs. Like other jobs, you can monitor queued jobs in the Apex Jobs page.

## Queueable Apex

