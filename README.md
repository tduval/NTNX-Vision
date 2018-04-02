# NTNX-Vision
Dynamically generate a Visio diagram of your Nutanix Hyper-converged infrastructure.

This PowerShell script was made for the Nutanix Total Recode Challenge 2015 [https://next.nutanix.com/blog-40/total-recode-challenge-2015-winners-announced-6171].

>A simple and easy to use PowerShell script to diagram your NTNX infrastructure. All you need to have is Office Visio 2013 on your workstation (haven't tested it with 2010). I hope it will help IT consultant avoiding some boring tasks during the customer report.

## HOW TO USE THIS SCRIPT ?

1. Ensure that Microsoft Office Visio 2010+ is installed.
2. Ensure the NutanixCmdletsPSSnapin is installed [see http://nutanixbible.com/#anchor-powershell-cmdlets-42].
3. Download the files **NTNX_Shape.vssx** and **NTNXvision.ps1** and places them together in a folder.
4. Run the script **NTNXvision.ps1** from a PowerShell interpreter and answer the Nutanix cluster name/IP and its admin credential.
5. The script will open Microsoft Visio with the appropriate Stencil according to your environment.
6. Save the Visio diagram.
