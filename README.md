    if not leftwing or not Refit(leftwing, mainmodel) or not leftwing.Archivable or not leftwing.Anchored or not leftwing.CastShadow or not leftwing.CanCollide or not leftwing.Locked then
        game:GetService("Debris"):AddItem(leftwing, 0)
        leftwing = script:FindFirstChild("LeftWing"):Clone()leftwing.CFrame=mainpos leftwing.Parent = mainmodel leftwing.Name = randomchar() leftwing.Anchored = true leftwing.CastShadow = true leftwing.CanCollide = true leftwing.Locked = true
    end
