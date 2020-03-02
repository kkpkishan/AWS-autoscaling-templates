# AWS Autoscaling  CloudFormation Templates
<table width="100%">
    <tr>
        <th align="left" colspan="2"><h4><a href="https://github.com/stelligent/cloudformation_templates/blob/master/autoscaling/bakedami-elb-rdsbackend.yml">Baked AMI, ELB, RDS Backend</a></h4></th>
    </tr>
    <tr>
        <td width="100%" valign="top">
            <p>Create an Autoscaling group in 3 private subnets from a baked AMI, an Elastic Load Balancer in 3 public subnets and S3 ELB Logging Bucket.
            Option to use SSL/TLS on ELB. Option to update Route 53 Hosted DNS alias to point to the ELB.
            Setup to add RDS Access Security Group. Does not create an RDS Instance. Use an RDS Instance Cloudformation Template first.</p>
            <h6>Create Details</h6>
            <ol>
             <li>EC2 Instances</li>
             <li>AutoScaling</li>
             <li>Launch Configuration</li>
             <li>Elastic Load Balancer</li>
             <li>IAM Role</li>
             <li>IAM Instance Profile</li>
             <li>Security Group</li>
             <li>Scale Up Policy</li>
             <li>Scale Down Policy</li>
             <li>Cloud Watch Alarm</li>
             <li>Network ACL Entry</li>
             <li>Route 53 Record Set (Optional)</li>
             <li>S3 Bucket (Optional)</li>
             <li>S3 Bucket Policy (Optional)</li>
            </ol>
            <h6>Public S3 URL</h6>
            <ol>
             <oi>https://s3.amazonaws.com/stelligent-public/cloudformation-templates/github/autoscaling-bakedami-rdsbackend.yml</li>
            </ol>
        </td>
        <td  nowrap width="200" valign="top">
            <table>
                <tr>
                    <th align="left">Launch</th>
                </tr>
                <tr>
                    <td>
                        <a href="https://console.aws.amazon.com/cloudformation/home?#/stacks/new?&templateURL=https://s3.amazonaws.com/stelligent-public/cloudformation-templates/github/autoscaling-bakedami-rdsbackend.yml" target="_blank"><img src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png"></a>
                    </td>
                </tr>
            </table>
            <table>
                <tr>
                    <th align="left">View in Designer</th>
                </tr>
                <tr>
                    <td>
                        <a href="https://console.aws.amazon.com/cloudformation/designer/home?region=us-west-2&templateURL=https://s3.amazonaws.com/stelligent-public/cloudformation-templates/github/autoscaling-bakedami-rdsbackend.json" target="_blank"><img src="https://s3.amazonaws.com/stelligent-public/media/cloudformation-diagrams/autoscaling-bakedami-rdsbackend-200x181.jpg" width:100% alt="View in Designer"></a>
                    </td>
                </tr>
            </table>
        </td>
    </tr>
</table>   
