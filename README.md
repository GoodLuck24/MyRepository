# MyRepository

<bean id="urge.JobDetail" class="org.springframework.scheduling.quartz.JobDetailBean">
		<property name="jobClass">
			<value>com.hollycrm.service.compensation.job.UrgeOrderJob</value>
		</property>
</bean>
