node {
echo("pipeline test");
echo("another pipeline test");
	stage('Init')	{
		echo ('Init stage');
		def z = new org.antonb.shared.shared();
		z.init();
		constants.Url = "www.spb.ru";
		echo constants.Url;
		echo ('Init stage end');
	}
}
