# SCA-Cloud-School-Application

# BRIEF EXPLANATION OF THE JENKINS 3 STAGES PIPELINE SYNTAX

**Source(git):**  Defines source control repository set up for the project


**Build Stage:**  For many projects the beginning of "work" in the Pipeline would be the "build" stage.
 This stage of the Pipeline is  where source code is assembled, compiled, or packaged.


**Deploy Stage:**  Deployment can imply a variety of steps, depending on the project or organization requirements,
and may be anything from publishing built artifacts to an Artifactory server, to pushing code to a
production system.

At this stage of the example Pipeline, both the "Build" and "Test" stages have successfully executed.
In essense, the "Deploy" stage will only execute assuming previous stages completed successfully,
otherwise the Pipeline would have exited early.
