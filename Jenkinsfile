#!/usr/bin/env groovy
import com.continuousx.jenkins.logger.LogLevelType
import com.continuousx.jenkins.pipelines.mavenbuild.PipelineMavenBuildConfig
import org.jenkinsci.plugins.workflow.libs.Library

@Library(['jenkins-cx-shared-library@feature/refactoring']) _

PipelineGlobal(new PipelineMavenBuildConfig(logLevelType: LogLevelType.INFO)
        .configStageGHProtectionCheck(true,true)
        .configStageScanHost(true,true)
)
