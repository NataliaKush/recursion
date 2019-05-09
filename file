<?php
 getFiles('directory');

 Function getFiles($dir) {
 	$files = array_diff(scandir($dir),['..','.']);
	
	foreach ($files as $file) { 
		$path = $dir . '/directory' . $file;
		
		if (is_dir($path)) {
			getfiles($path);
		 } else {
			var_dump($path);
		}
	
	}

}
