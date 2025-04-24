# Operations and Management Review Checklist

## Operational Considerations

   1.  Has deployment been discussed?

       *  Does the document include a description of how this protocol
          or technology is going to be deployed and managed?

       *  Is the proposed specification deployable?  If not, how could
          it be improved?

       *  Does the solution scale well from the operational and
          management perspective?  Does the proposed approach have any
          scaling issues that could affect usability for large-scale
          operation?

       *  Are there any coexistence issues?

   2.  Has installation and initial setup been discussed? 

       *  Is the solution sufficiently configurable?

       *  Are configuration parameters clearly identified?

       *  Are configuration parameters normalized?

       *  Does each configuration parameter have a reasonable default
          value?

       *  Will configuration be pushed to a device by a configuration
          manager, or pulled by a device from a configuration server?

       *  How will the devices and managers find and authenticate each
          other?

   3.  Has the migration path been discussed?

       *  Are there any backward compatibility issues?

   4.  Have the Requirements on other protocols and functional
       components been discussed?

       *  What protocol operations are expected to be performed relative
          to the new protocol or technology, and what protocols and data
          models are expected to be in place or recommended to ensure
          for interoperable management?

   5.  Has the impact on network operation been discussed?  

       *  Will the new protocol significantly increase traffic load on
          existing networks?

       *  Will the proposed management for the new protocol
          significantly increase traffic load on existing networks?

       *  How will the new protocol impact the behavior of other
          protocols in the network?  Will it impact performance (e.g.,
          jitter) of certain types of applications running in the same
          network?

       *  Does the new protocol need supporting services (e.g., DNS or
          Authentication, Authorization, and Accounting - AAA) added to
          an existing network?

   6.  Have suggestions for verifying correct operation been discussed?

       *  How can one test end-to-end connectivity and throughput?

       *  Which metrics are of interest?

       *  Will testing have an impact on the protocol or the network?

   7.  Has management interoperability been discussed?

       *  Is a standard protocol needed for interoperable management?

       *  Is a standard information or data model needed to make
          properties comparable across devices from different vendors?

   8.  Are there fault or threshold conditions that should be reported?

       *  Does specific management information have time utility?

       *  Should the information be reported by notifications?  Polling?
          Event-driven polling?

       *  Is notification throttling discussed?

       *  Is there support for saving state that could be used for root
          cause analysis?

   9.  Is configuration discussed?

       *  Are configuration defaults and default modes of operation
          considered?

       *  Is there discussion of what information should be preserved
          across reboots of the device or the management system?  Can
          devices realistically preserve this information through hard
          reboots where physical configuration might change (e.g., cards
          might be swapped while a chassis is powered down)?

## Management Considerations

   Do you anticipate any manageability issues with the specification?

   1.  Is management interoperability discussed?

       *  Will it use centralized or distributed management?

       *  Will it require remote and/or local management applications?

       *  Are textual or graphical user interfaces required?

       *  Is textual or binary format for management information
          preferred?

   2.  Is management information discussed?

       *  What is the minimal set of management (configuration, faults,
          performance monitoring) objects that need to be instrumented
          in order to manage the new protocol?

   3.  Is fault management discussed?

       *  Is Liveness Detection and Monitoring discussed?

       *  Does the solution have failure modes that are difficult to
          diagnose or correct?  Are faults and alarms reported and
          logged?

   4.  Is configuration management discussed?

       *  Is protocol state information exposed to the user?  How?  Are
          significant state transitions logged?

   5.  Is accounting management discussed?

   6.  Is performance management discussed?

       *  Does the protocol have an impact on network traffic and
          network devices?  Can performance be measured?

       *  Is protocol performance information exposed to the user?

   7.  Is security management discussed?

       *  Does the specification discuss how to manage aspects of
          security, such as access controls, managing key distribution,
          etc.

##  Documentation

   1. Is an operational considerations and/or manageability section part of
   the document?

   2. Does the proposed protocol have a significant operational impact on
   the Internet?

   3. Is there proof of implementation and/or operational experience?
