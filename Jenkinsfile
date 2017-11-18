#!/usr/bin/env groovy

node {
	try {
		if(env.MY_VAR?.contains('CDL2017')) {
			def tasks = ['bim', 'bam', 'bilim']
			tasks.each { task ->
				echo "Triggering  task $task ..."
			}
		} else {
			echo "No CDL2017 ..."
		}
	} catch (e) {
		echo "Ouch!"
	}
}
