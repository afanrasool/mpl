@Library('mpl') _

// Use default master pipeline
MPLPipeline {
  // Pipeline configuration override here
  // Example: (check available options in the pipeline definition)
  agent_label = 'mavey'                     // Set agent label
  modules.Build.tool_version = 'Maven 2' // Change tool for build stage
  modules.Test = null                    // Disable Test stage
}
