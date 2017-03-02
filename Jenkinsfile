node {
echo("pipeline test");
echo("another pipeline test");
	stage('Init')	{
		echo ('Init stage');
		def z = new org.antonb.shared.shared();
		z.init();
		constants.url = "www.spb.ru";
		constants.fullUrl();
		echo ('Init stage end');
	}
}
