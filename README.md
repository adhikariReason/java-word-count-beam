Reason Adhikari

 * Generate a Maven project that contains Beam’s WordCount
 * Get sample text
 * Run pipeline: "mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount ` -D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner"
 * Output file should be created


 PageRank Using MinimalWordCount
    Changed to MinimalPageRankAdhikari
*  Run pipeline: "mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.MinimalPageRankAdhikari ` -D exec.args="--inputFile=README.md --output=adhikariOutput" -P direct-runner"
 
