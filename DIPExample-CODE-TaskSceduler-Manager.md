class Program
{
	static void Main(string[] args)
	{
		TaskScheduler taskScheduler = new TaskScheduler();
		taskScheduler.ScheduleTask(new PriorityQueue());
	}
}
public class TaskScheduler
{
	public void ScheduleTask(IQueueDS taskQueue)
	{
		//logic
	}
}
public interface IQueueDS
{
	void Enqueue(string taskName);
	void Dequeue();
	void ClearQueue();
 }
public class PriorityQueue: IQueueDS
{
	private Queue queue;
	public PriorityQueue()
	{
		queue = new Queue();
	}
}