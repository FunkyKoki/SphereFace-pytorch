# SphereFace in Pytorch

In the loss function code, the author set a 'Focal loss' as:
`pt = logit.data.exp()
loss = -1 * (1 - pt) ** self.gamma * logit`
